[app](../../../index.md) / [com.otago.open](../../index.md) / [PDFListFragment](../index.md) / [PDFService](index.md) / [determinePath](./determine-path.md)

# determinePath

`fun determinePath(currentDir: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, href: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paperUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`

Determines where a [href](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/href) on a page given by [currentDir](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/currentDir) should point, if [currentDir](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/currentDir) is
a file (i.e. no forward slash), otherwise when in the folder given by [currentDir](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/currentDir)

If [href](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/href) starts with a "/" We just return the href with the [paperUrl](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/paperUrl) removed

The return is relative to [paperUrl](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/paperUrl)

### Parameters

`currentDir` - The current folder or page

`href` - The href

`paperUrl` - The base url for the course

**Return**
Where [href](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/href) should point (relative to [paperUrl](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/paperUrl)) if it appears at [currentDir](determine-path.md#com.otago.open.PDFListFragment.PDFService$determinePath(kotlin.String, kotlin.String, kotlin.String)/currentDir)

