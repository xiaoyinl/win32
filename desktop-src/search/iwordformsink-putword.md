---
Description: Puts the original word form in the IWordFormSink object.
ms.assetid: 333A3109-6C0A-42AE-9E10-87F53C7F737C
title: IWordFormSink::PutWord method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# IWordFormSink::PutWord method

Puts the original word form in the [**IWordFormSink**](/windows/desktop/api/Indexsrv/nn-indexsrv-iwordformsink) object.

## Syntax


```C++
HRESULT PutWord(
  [in] const WCHAR *pwcInBuf ,
  [in]       ULONG cwc
);
```



## Parameters

<dl> <dt>

*pwcInBuf* \[in\]
</dt> <dd>

A pointer to a buffer that contains the final alternative form of a word, which is always the original word.

</dd> <dt>

*cwc* \[in\]
</dt> <dd>

The number of characters in *pwcInBuf*.

</dd> </dl>

## Return value

This method can return one of these values.



| Return code                                                                          | Description                                           |
|--------------------------------------------------------------------------------------|-------------------------------------------------------|
| <dl> <dt>**S\_OK**</dt> </dl> | The operation was completed successfully. <br/> |



 

## Remarks

**PutWord** is called from the [**GenerateWordForms**](https://msdn.microsoft.com/windows/desktop/7996468d-3b5f-4bfc-837d-51082655cbbc) method of the [**IStemmer**](https://msdn.microsoft.com/windows/desktop/1a6e77ec-60f8-4e43-9420-7a6b50152e26) implementation. This method handles the original form of a word and is called last. All preceding alternative forms for a word are put in the [**IWordFormSink**](/windows/desktop/api/Indexsrv/nn-indexsrv-iwordformsink) object by calling [**IWordFormSink::PutAltWord**](iwordformsink-putphrase.md).

## Requirements



|                                     |                                                                                     |
|-------------------------------------|-------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 2000 Professional \[desktop apps only\]<br/>                          |
| Minimum supported server<br/> | Windows 2000 Server \[desktop apps only\]<br/>                                |
| Header<br/>                   | <dl> <dt>Search.h</dt> </dl> |



## See also

<dl> <dt>

[**IWordFormSink**](/windows/desktop/api/Indexsrv/nn-indexsrv-iwordformsink)
</dt> </dl>

 

 



