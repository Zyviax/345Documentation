[app](../../index.md) / [com.otago.open](../index.md) / [PDFListFragment](./index.md)

# PDFListFragment

`class PDFListFragment : Fragment`

A [Fragment](#) that generates each [PDFItem](../-p-d-f-item/index.md) to display.

### Types

| Name | Summary |
|---|---|
| [FetchResult](-fetch-result/index.md) | `data class FetchResult` |
| [PDFService](-p-d-f-service/index.md) | Coordinates fetching and downloading PDF files from a url. Use [PDFService.startService](-p-d-f-service/start-service.md) to begin coroutines will fetch, and then download each PDF.`object PDFService` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A [Fragment](#) that generates each [PDFItem](../-p-d-f-item/index.md) to display.`PDFListFragment()` |

### Functions

| Name | Summary |
|---|---|
| [onActivityCreated](on-activity-created.md) | Create the items to display upon starting the fragment. All items are pulled from one directory`fun onActivityCreated(savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | Entry point for creating a [PDFListFragment](./index.md) Ensure that the instance is retained on back button press`fun onCreate(savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | Entry point of the [PDFListFragment](./index.md) view.`fun onCreateView(inflater: `[`LayoutInflater`](https://developer.android.com/reference/android/view/LayoutInflater.html)`, container: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`?, savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`View`](https://developer.android.com/reference/android/view/View.html)`?` |
