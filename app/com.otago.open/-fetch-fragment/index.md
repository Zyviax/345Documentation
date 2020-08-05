[app](../../index.md) / [com.otago.open](../index.md) / [FetchFragment](./index.md)

# FetchFragment

`class FetchFragment : Fragment`

The class for the fragment to fetch the courses

### Types

| Name | Summary |
|---|---|
| [CourseService](-course-service/index.md) | Coordinates fetching the course web-pages from the university website Use [CourseService.startService](-course-service/start-service.md) to begin`object CourseService` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | The class for the fragment to fetch the courses`FetchFragment()` |

### Functions

| Name | Summary |
|---|---|
| [onActivityCreated](on-activity-created.md) | Handles the creation of this activity, and starts the coroutine service to list the courses`fun onActivityCreated(savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | Entry point for creating a [FetchFragment](./index.md) Ensure that the instance is retained on back button press`fun onCreate(savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | Entry point of the [FetchFragment](./index.md) view.`fun onCreateView(inflater: `[`LayoutInflater`](https://developer.android.com/reference/android/view/LayoutInflater.html)`, container: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`?, savedInstanceState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`?): `[`View`](https://developer.android.com/reference/android/view/View.html)`?` |
| [onSaveInstanceState](on-save-instance-state.md) | Event handler for saving the state when the user navigates away or rotates the screen`fun onSaveInstanceState(outState: `[`Bundle`](https://developer.android.com/reference/android/os/Bundle.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRecyclerItems](set-recycler-items.md) | Sets the items in the recycler based on the provided [CourseItem](../-course-item/index.md)s`fun setRecyclerItems(links: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CourseItem`](../-course-item/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
