[app](../../index.md) / [com.otago.open](../index.md) / [PDFItemRecyclerViewAdapter](./index.md)

# PDFItemRecyclerViewAdapter

`class PDFItemRecyclerViewAdapter : Adapter<ViewHolder>`

A standard [RecyclerView.Adapter](#) to display PDF items.
The adapter binds the view holders to their data.

### Parameters

`list` - The list of [PDFItem](../-p-d-f-item/index.md)s

`listener` - The function to execute if a PDF is selected

**See Also**

[PDFItemRecyclerViewAdapter](./index.md)

[PDFListFragment](../-p-d-f-list-fragment/index.md)

### Types

| Name | Summary |
|---|---|
| [ViewHolder](-view-holder/index.md) | The [RecyclerView.ViewHolder](#) to bind [PDFItem](../-p-d-f-item/index.md)s to recycler entries`class ViewHolder : ViewHolder` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A standard [RecyclerView.Adapter](#) to display PDF items. The adapter binds the view holders to their data.`PDFItemRecyclerViewAdapter(list: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`PDFItem`](../-p-d-f-item/index.md)`>, listener: (`[`PDFItem`](../-p-d-f-item/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`)` |

### Functions

| Name | Summary |
|---|---|
| [getItemCount](get-item-count.md) | Gets the amount of items in this recycler`fun getItemCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [onBindViewHolder](on-bind-view-holder.md) | Handles the binding of the [ViewHolder](-view-holder/index.md) to a [PDFItem](../-p-d-f-item/index.md)`fun onBindViewHolder(holder: ViewHolder, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateViewHolder](on-create-view-holder.md) | Entry point of [PDFItemRecyclerViewAdapter](./index.md).`fun onCreateViewHolder(parent: `[`ViewGroup`](https://developer.android.com/reference/android/view/ViewGroup.html)`, viewType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): ViewHolder` |
