[app](../../../index.md) / [com.otago.open](../../index.md) / [CourseItemRecyclerViewAdapter](../index.md) / [ViewHolder](./index.md)

# ViewHolder

`class ViewHolder : ViewHolder`

The [RecyclerView.ViewHolder](#) to bind [CourseItem](../../-course-item/index.md)s to recycler entries

### Parameters

`itemView` - The recycler item view to bind to

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | The [RecyclerView.ViewHolder](#) to bind [CourseItem](../../-course-item/index.md)s to recycler entries`ViewHolder(itemView: `[`View`](https://developer.android.com/reference/android/view/View.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [imageView](image-view.md) | The recycler image view`val imageView: `[`ImageView`](https://developer.android.com/reference/android/widget/ImageView.html) |
| [textView1](text-view1.md) | The recycler's first (main) text view`val textView1: `[`TextView`](https://developer.android.com/reference/android/widget/TextView.html) |
| [textView2](text-view2.md) | The recycler's second (auxiliary) text view`val textView2: `[`TextView`](https://developer.android.com/reference/android/widget/TextView.html) |

### Functions

| Name | Summary |
|---|---|
| [bind](bind.md) | Binds a [CourseItem](../../-course-item/index.md) to a recycler [View](https://developer.android.com/reference/android/view/View.html)`fun bind(item: `[`CourseItem`](../../-course-item/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
