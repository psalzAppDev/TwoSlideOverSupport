# SupportDocs: DataSource
This branch is where SupportDocs gets its data! You can add, edit, and delete documents here. For usage instructions, check out the `README`'s [usage](https://github.com/aheze/SupportDocs#using-the-github-repository) section in the main branch.

## Data Source JSON URL
<a href="https://raw.githubusercontent.com/psalzAppDev/TwoSlideOverSupport/DataSource/_data/supportdocs_datasource.json">https://raw.githubusercontent.com/psalzAppDev/TwoSlideOverSupport/DataSource/_data/supportdocs_datasource.json</a>

<details markdown="1">
<summary><strong>Show examples</strong></summary>

<hr>

### SwiftUI
```swift
struct SwiftUIExampleView_MinimalCode: View {
    let dataSource = URL(string: "https://raw.githubusercontent.com/psalzAppDev/TwoSlideOverSupport/DataSource/_data/supportdocs_datasource.json")!
    @State var supportDocsPresented = false
    
    var body: some View {
        Button("Present SupportDocs from SwiftUI!") { supportDocsPresented = true }
        .sheet(isPresented: $supportDocsPresented, content: {
            SupportDocsView(dataSource: dataSource, isPresented: $supportDocsPresented)
        })
    }
}
```

### UIKit
```swift
class UIKitExampleController_MinimalCode: UIViewController {
    /**
    Connect this inside the storyboard.
    
    This is just for demo purposes, so it's not connected yet.
    */
    @IBAction func presentButtonPressed(_ sender: Any) {
        let dataSource = URL(string: "https://raw.githubusercontent.com/psalzAppDev/TwoSlideOverSupport/DataSource/_data/supportdocs_datasource.json")!
    
        let supportDocsViewController = SupportDocsViewController(dataSource: dataSource)
        self.present(supportDocsViewController, animated: true, completion: nil)
    }
}
```

<hr>

</details>

## Table of Contents
- [404 Page](https://psalzAppDev.github.io/TwoSlideOverSupport/404) (SupportDocs Integrated File) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/TwoSlideOverSupport/404.md))
- [Apple smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/Apple) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/Apple.md))
- [ASCIIfy Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor/Effect_ASCIIfy) (TwoSlideOver, effect, asciify) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor/Effect_ASCIIfy.md))
- [Blueberry smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/Blueberry) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/Blueberry.md))
- [Bright Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filters_bright) (TwoSlideOver, filter, bright) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filters_bright.md))
- [Buy blue boba](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Boba/BuyBlueBoba) (boba) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Boba/BuyBlueBoba.md))
- [Buy cream boba](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Boba/BuyCreamBoba) (boba) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Boba/BuyCreamBoba.md))
- [Buy orange boba](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Boba/BuyOrangeBoba) (boba) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Boba/BuyOrangeBoba.md))
- [Filters](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filters_general) (filter) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filters_general.md))
- [How to cook pizza](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToCookPizza) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToCookPizza.md))
- [How to eat burritos](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToEatBurritos) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToEatBurritos.md))
- [How to eat grilled cheese](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToEatGrilledCheese) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToEatGrilledCheese.md))
- [How to eat nachos](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToEatNachos) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToEatNachos.md))
- [How to eat tacos](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToEatTacos) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToEatTacos.md))
- [How to make spaghetti](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToMakeSpaghetti) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToMakeSpaghetti.md))
- [How to prepare ramen](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToPrepareRamen) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToPrepareRamen.md))
- [Import Photo](https://psalzAppDev.github.io/TwoSlideOverSupport/General/ImportPhoto) (TwoSlideOver, import) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/General/ImportPhoto.md))
- [Peach smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/Peach) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/Peach.md))
- [Photo Editor](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor/PhotoEditor_Overview) (TwoSlideOver, PhotoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor/PhotoEditor_Overview.md))
- [Plum smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/Plum) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/Plum.md))
- [Red berry smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/RedBerries) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/RedBerries.md))
- [Share Photo](https://psalzAppDev.github.io/TwoSlideOverSupport/General/SharePhoto) (TwoSlideOver, share) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/General/SharePhoto.md))
- [Slide To Compare](https://psalzAppDev.github.io/TwoSlideOverSupport/General/SlideToCompare) (TwoSlideOver, slide, compare) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/General/SlideToCompare.md))
- [Summer Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filters_summer) (filter, summer) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filters_summer.md))
- [Triangulation Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor/Effect_Triangulation) (TwoSlideOver, effect, triangulation) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor/Effect_Triangulation.md))


## Notes
- Your changes make take up to five minutes to deploy. You can track the deployment progress [here](https://github.com/psalzAppDev/TwoSlideOverSupport/deployments/activity_log?environment=github-pages).
- Do **not** update this file (`README.md`) directly. Your changes will be overriden the next time you push (the GitHub Action will regenerate this file). Instead, update the file in [`_scripts/README.md`](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/_scripts/README.md). 