[app](../../index.md) / [com.otago.open](../index.md) / [PDFItem](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`PDFItem(imageResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, pathType: `[`FileNavigatorType`](../-file-navigator-type/index.md)`, paperFolder: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paperUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, pathSubName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, prettyPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`

Data class for the PDF items in the [PDFListFragment](../-p-d-f-list-fragment/index.md)

### Parameters

`imageResource` - The index of imageResource to use from project

`pathType` - The type of item at the path (folder, PDF, etc)

`paperFolder` - The base directory for the paper (e.g. /data/android_stuff_here/COSC***)

`paperUrl` - The base URL for the paper (e.g. https://cs.otago.ac.nz/COSC***)

`pathSubName` - The rest of the folder name or URL for a resource, e.g. lectures.php/Lecture01.pdf

`prettyPath` - The pretty name for the path (e.g. lectures.php -&gt; Lectures)