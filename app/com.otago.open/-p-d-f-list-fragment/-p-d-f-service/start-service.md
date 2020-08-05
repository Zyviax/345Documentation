[app](../../../index.md) / [com.otago.open](../../index.md) / [PDFListFragment](../index.md) / [PDFService](index.md) / [startService](./start-service.md)

# startService

`fun startService(paperFolder: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paperUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paperSubName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, inFragment: `[`PDFListFragment`](../index.md)`, doFolders: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Starts fetching and downloading PDFs.
Utilises coroutines to run networking on a separate threads to UI.

### Parameters

`paperFolder` - The folder in which the paper's downloaded content is stored

`paperUrl` - The URL at which course PDFs are located

`paperSubName` - The resource over which we are enumerating (e.g. looking for folders in index.php or PDFs in lectures.php)

`inFragment` - The instance of [PDFListFragment](../index.md), to call in class functions

`doFolders` - Whether we want to include folders. Currently this should only be true if paperSubName is "" or "index.php" due to the COSC website navigation structure

**See Also**

[fetchLinks](#)

[downloadPDF](#)

[PDFItem](../../-p-d-f-item/index.md)

