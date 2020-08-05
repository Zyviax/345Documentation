[app](../../../index.md) / [com.otago.open](../../index.md) / [PDFListFragment](../index.md) / [PDFService](index.md) / [generatePdfItems](./generate-pdf-items.md)

# generatePdfItems

`fun generatePdfItems(fetched: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<FetchResult>): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PDFItem`](../../-p-d-f-item/index.md)`>`

Creates [PDFItem](../../-p-d-f-item/index.md)s from [FetchResult](../-fetch-result/index.md)s by deciding on the pretty name and the icon to use.

### Parameters

`fetched` - The fetched / chosen PDFs / folders

**Return**
The processed list of [FetchResult](../-fetch-result/index.md)s as a list of [PDFItem](../../-p-d-f-item/index.md)s

