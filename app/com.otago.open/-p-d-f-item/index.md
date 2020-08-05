[app](../../index.md) / [com.otago.open](../index.md) / [PDFItem](./index.md)

# PDFItem

`data class PDFItem`

Data class for the PDF items in the [PDFListFragment](../-p-d-f-list-fragment/index.md)

### Parameters

`imageResource` - The index of imageResource to use from project

`pathType` - The type of item at the path (folder, PDF, etc)

`paperFolder` - The base directory for the paper (e.g. /data/android_stuff_here/COSC***)

`paperUrl` - The base URL for the paper (e.g. https://cs.otago.ac.nz/COSC***)

`pathSubName` - The rest of the folder name or URL for a resource, e.g. lectures.php/Lecture01.pdf

`prettyPath` - The pretty name for the path (e.g. lectures.php -&gt; Lectures)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Data class for the PDF items in the [PDFListFragment](../-p-d-f-list-fragment/index.md)`PDFItem(imageResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, pathType: `[`FileNavigatorType`](../-file-navigator-type/index.md)`, paperFolder: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, paperUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, pathSubName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, prettyPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [imageResource](image-resource.md) | The index of imageResource to use from project`val imageResource: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [paperFolder](paper-folder.md) | The base directory for the paper (e.g. /data/android_stuff_here/COSC***)`val paperFolder: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [paperUrl](paper-url.md) | The base URL for the paper (e.g. https://cs.otago.ac.nz/COSC***)`val paperUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pathSubName](path-sub-name.md) | The rest of the folder name or URL for a resource, e.g. lectures.php/Lecture01.pdf`val pathSubName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [pathType](path-type.md) | The type of item at the path (folder, PDF, etc)`val pathType: `[`FileNavigatorType`](../-file-navigator-type/index.md) |
| [prettyPath](pretty-path.md) | The pretty name for the path (e.g. lectures.php -&gt; Lectures)`val prettyPath: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
