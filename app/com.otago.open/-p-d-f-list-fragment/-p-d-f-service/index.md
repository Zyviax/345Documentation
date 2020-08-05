[app](../../../index.md) / [com.otago.open](../../index.md) / [PDFListFragment](../index.md) / [PDFService](./index.md)

# PDFService

`object PDFService`

Coordinates fetching and downloading PDF files from a url.
Use [PDFService.startService](start-service.md) to begin coroutines will fetch,
and then download each PDF.

### Functions

| Name | Summary |
|---|---|
| [determinePath](determine-path.md) | Determines where a [href](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/href) on a page given by [currentDir](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/currentDir) should point, if [currentDir](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/currentDir) is a file (i.e. no forward slash), otherwise when in the folder given by [currentDir](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/currentDir)`fun determinePath(currentDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, href: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paperUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [generatePdfItems](generate-pdf-items.md) | Creates [PDFItem](../../-p-d-f-item/index.md)s from [FetchResult](../-fetch-result/index.md)s by deciding on the pretty name and the icon to use.`fun generatePdfItems(fetched: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FetchResult>): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PDFItem`](../../-p-d-f-item/index.md)`>` |
| [startService](start-service.md) | Starts fetching and downloading PDFs. Utilises coroutines to run networking on a separate threads to UI.`fun startService(paperFolder: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paperUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paperSubName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, inFragment: `[`PDFListFragment`](../index.md)`, doFolders: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
