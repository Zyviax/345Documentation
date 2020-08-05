[app](../../index.md) / [com.otago.open](../index.md) / [MarkViewFragment](./index.md)

# MarkViewFragment

`class MarkViewFragment : Fragment`

A [Fragment](#) to view marks.
Uses a WebView

### Types

| Name | Summary |
|---|---|
| [MarksService](-marks-service/index.md) | Sends an HTTP POST request to the CS website to grab some marks HTML.`object MarksService` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A [Fragment](#) to view marks. Uses a WebView`MarkViewFragment()` |

### Functions

| Name | Summary |
|---|---|
| [onCreateView](on-create-view.md) | Entry point of [MarkViewFragment](./index.md)`fun onCreateView(inflater: `[`LayoutInflater`](https://developer.android.com/reference/android/view/LayoutInflater.html)`, container: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`?, savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`View`](https://developer.android.com/reference/android/view/View.html)`?` |
| [onViewCreated](on-view-created.md) | Handles the creation of the views. Displays the marks`fun onViewCreated(view: `[`View`](https://developer.android.com/reference/android/view/View.html)`, savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
