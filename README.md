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
- [ASCIIfy Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor/Effect_ASCIIfy) (effect, asciify, PhotoEditorGeneral) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor/Effect_ASCIIfy.md))
- [Auto Enhance](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_autoEnhance) (edit, autoEnhance, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_autoEnhance.md))
- [Autumn Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_autumn) (filter, autumn, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_autumn.md))
- [Bloom Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_bloom) (filter, bloom, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_bloom.md))
- [Blueberry smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/Blueberry) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/Blueberry.md))
- [Blur Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Effects/effect_blur) (effect, blur, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Effects/effect_blur.md))
- [Box Blur Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Effects/effect_boxBlur) (effect, boxBlur, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Effects/effect_boxBlur.md))
- [Bright Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filters_bright) (filter, bright, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filters_bright.md))
- [Buy blue boba](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Boba/BuyBlueBoba) (boba) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Boba/BuyBlueBoba.md))
- [Buy cream boba](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Boba/BuyCreamBoba) (boba) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Boba/BuyCreamBoba.md))
- [Buy orange boba](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Boba/BuyOrangeBoba) (boba) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Boba/BuyOrangeBoba.md))
- [Chrome Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_chrome) (filter, chrome, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_chrome.md))
- [Cloudy Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_cloudy) (filter, cloudy, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_cloudy.md))
- [Colorless Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_colorless) (filter, colorless, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_colorless.md))
- [Comic Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Effects/effect_comicEffect) (effect, comicEffect, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Effects/effect_comicEffect.md))
- [Edit Brightness](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_brightness) (edit, brightness, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_brightness.md))
- [Edit Clarity](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_clarity) (edit, clarity, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_clarity.md))
- [Edit Contrast](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_contrast) (edit, contrast, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_contrast.md))
- [Edit Exposure](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_exposure) (edit, exposure, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_exposure.md))
- [Edit Fade](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_fade) (edit, fade, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_fade.md))
- [Edit Gamma Adjust](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_gammaAdjust) (edit, gamma, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_gammaAdjust.md))
- [Edit Highlights](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_highlights) (edit, highlights, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_highlights.md))
- [Edit Hue Adjust](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_hueAdjust) (edit, hueAdjust, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_hueAdjust.md))
- [Edit Saturation](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_saturation) (edit, saturation, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_saturation.md))
- [Edit Shadows](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_shadows) (edit, shadows, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_shadows.md))
- [Edit Temperature](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_temperature) (edit, temperature, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_temperature.md))
- [Edit Vibrancy](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_vibrancy) (edit, vibrancy, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_vibrancy.md))
- [Edit Vignette](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_vignette) (edit, vignette, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_vignette.md))
- [Edit White Point Adjust](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_whitePointAdjust) (edit, whitePointAdjust, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_whitePointAdjust.md))
- [Eight Bit Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Effects/effect_eightBit) (effect, eightBit, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Effects/effect_eightBit.md))
- [Fade Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_fade) (filter, fade, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_fade.md))
- [Filters](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filters_general) (filter, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filters_general.md))
- [Golden Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_golden) (filter, golden, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_golden.md))
- [How to cook pizza](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToCookPizza) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToCookPizza.md))
- [How to eat burritos](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToEatBurritos) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToEatBurritos.md))
- [How to eat grilled cheese](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToEatGrilledCheese) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToEatGrilledCheese.md))
- [How to eat nachos](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToEatNachos) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToEatNachos.md))
- [How to eat tacos](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToEatTacos) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToEatTacos.md))
- [How to make spaghetti](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToMakeSpaghetti) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToMakeSpaghetti.md))
- [How to prepare ramen](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-FastFood/HowToPrepareRamen) (fastFood) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-FastFood/HowToPrepareRamen.md))
- [Import Photo](https://psalzAppDev.github.io/TwoSlideOverSupport/General/ImportPhoto) (import, general) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/General/ImportPhoto.md))
- [Instant Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_instant) (filter, instant, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_instant.md))
- [Lens Distortion Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Effects/effect_lensDistortion) (effect, lensDistortion, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Effects/effect_lensDistortion.md))
- [Mono Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_mono) (filter, mono, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_mono.md))
- [Noir Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_noir) (filter, noir, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_noir.md))
- [Peach smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/Peach) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/Peach.md))
- [Photo Editor](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor/PhotoEditor_Overview) (TwoSlideOver, PhotoEditor, PhotoEditorGeneral) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor/PhotoEditor_Overview.md))
- [Plum smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/Plum) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/Plum.md))
- [Privacy](https://psalzAppDev.github.io/TwoSlideOverSupport/General/Privacy) (privacy, general) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/General/Privacy.md))
- [Process Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_process) (filter, process, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_process.md))
- [Rainy Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_rainy) (filter, rainy, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_rainy.md))
- [Red berry smoothie](https://psalzAppDev.github.io/TwoSlideOverSupport/Sample-Smoothies/RedBerries) (smoothies) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/Sample-Smoothies/RedBerries.md))
- [Share Photo](https://psalzAppDev.github.io/TwoSlideOverSupport/General/SharePhoto) (general, share) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/General/SharePhoto.md))
- [Sharpen](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Edits/edit_sharpen) (edit, sharpen, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Edits/edit_sharpen.md))
- [Silver Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_silver) (filter, silver, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_silver.md))
- [Slide To Compare](https://psalzAppDev.github.io/TwoSlideOverSupport/General/SlideToCompare) (general, slide, compare) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/General/SlideToCompare.md))
- [Summer Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filters_summer) (filter, summer, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filters_summer.md))
- [Sunny Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_sunny) (filter, sunny, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_sunny.md))
- [Surface Blur Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Effects/effect_surfaceBlur) (effect, surfaceBlur, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Effects/effect_surfaceBlur.md))
- [Tonal Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_tonal) (filter, tonal, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_tonal.md))
- [Transfer Filter](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor_Filters/filter_transfer) (filter, transfer, photoEditor) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor_Filters/filter_transfer.md))
- [Triangulation Effect](https://psalzAppDev.github.io/TwoSlideOverSupport/PhotoEditor/Effect_Triangulation) (effect, triangulation, PhotoEditorGeneral) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/PhotoEditor/Effect_Triangulation.md))
- [TwoSlideOver Overview](https://psalzAppDev.github.io/TwoSlideOverSupport/General/Overview) (overview, general) ([edit](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/General/Overview.md))


## Notes
- Your changes make take up to five minutes to deploy. You can track the deployment progress [here](https://github.com/psalzAppDev/TwoSlideOverSupport/deployments/activity_log?environment=github-pages).
- Do **not** update this file (`README.md`) directly. Your changes will be overriden the next time you push (the GitHub Action will regenerate this file). Instead, update the file in [`_scripts/README.md`](https://github.com/psalzAppDev/TwoSlideOverSupport/edit/DataSource/_scripts/README.md). 