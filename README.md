# react-native-swiper

![logo](https://d13yacurqjgara.cloudfront.net/users/60166/screenshots/1688473/sea_water.jpg)

The best Swiper component for React Native.

## FEAUTURE & TODO

- [x] Infinite loop

- [x] Direction control

- [x] Complete custom style

- [x] Allow title display & custom

- [x] Multiple instances

- [x] Custom container size

- [x] Control buttons

- [x] Autoplay

- [ ] More switch effects

- [ ] Unit tests

- [ ] logo

## Getting Started

- [Installation](#installation)
- [Properties](#properties)
- [Examples](#examples)
- [Development](#development)

### Installation

### Properties

#### Basic

| Prop  | Default  | Type | Describe |
| :------------ |:---------------:| :---------------:| :-----|
| horizontal | true | bool | xx |
| loop | true | bool | xx |
| index | 0 | number | xx |
| showsButtons | false | bool | xx |
| autoplay | false | bool | xx |

#### Custom basic style & content

| Prop  | Default  | Type | Describe |
| :------------ |:---------------:| :---------------:| :-----|
| width | - | number | default: fullscreen with `flex: 1` |
| height | - | number | default: fullscreen with `flex: 1` |
| style | {...} | react-styles | see default style in source |

#### Pagination

| Prop  | Default  | Type | Describe |
| :------------ |:---------------:| :---------------:| :-----|
| showsPagination | true | bool | xx |
| dot | ```jsx
<View style={{backgroundColor:'rgba(0,0,0,.2)', width: 8, height: 8,borderRadius: 4, marginLeft: 3, marginRight: 3, marginTop: 3, marginBottom: 3,}} />
``` | react-dom | allow you custom the dot element |
| activeDot | `<View style={{backgroundColor: '#007aff', width: 8, height: 8, borderRadius: 4, marginLeft: 3, marginRight: 3, marginTop: 3, marginBottom: 3,}} />` | react-dom | allow you custom the active-dot element |

#### Autoplay

| Prop  | Default  | Type | Describe |
| :------------ |:---------------:| :---------------:| :-----|
| autoplay | true | bool | xx |
| autoplayTimeout | 2.5 | $12 | (second) |
| autoplayDirection | true | bool | cicy direction control |

#### Control buttons

| Prop  | Default  | Type | Describe |
| :------------ |:---------------:| :---------------:| :-----|
| showsButtons | true | $1600 | xx |
| showsButtons | true | $1600 | xx |

#### Props of Children

| Prop  | Default  | Type | Describe |
| :------------ |:---------------:| :---------------:| :-----|
| style | true | $1600 | merge |
| title | {<Text numberOfLines={1}>...</Text>} | `<Text />` | only show if |

#### Basic props of `<ScrollView />`

| Prop  | Default  | Type | Describe |
| :------------ |:---------------:| :---------------:| :-----|
| horizontal | true | bool | xx |
| pagingEnabled | true | bool | xx |
| showsHorizontalScrollIndicator | false | bool | xx |
| showsVerticalScrollIndicator | false | bool | xx |
| bounces | false | bool | xx |
| scrollsToTop | false | bool | xx |
| removeClippedSubviews | true | bool | xx |
| automaticallyAdjustContentInsets | false | bool | xx |

> @see: http://facebook.github.io/react-native/docs/scrollview.html

#### Supported ScrollResponder

| Prop  | Default  | Type | Describe |
| :------------ |:---------------:| :---------------:| :-----|
| onMomentumScrollBegin | - | function | when animation begins after letting up |
| onMomentumScrollEnd | - | function | Makes no sense why this occurs first during bounce |
| onTouchStartCapture | - | function | immediately after `onMomentumScrollEnd` |
| onTouchStart | - | function | same, but bubble phase |
| onTouchEnd | - | function | You could hold the touch start for a long time |
| onResponderRelease | - | function | when lifting up - you could pause forever before * lifting |

> @see: https://github.com/facebook/react-native/blob/master/Libraries/Components/ScrollResponder.js

### Examples

### Development

## Contribution

- [@leecade](mailto:leecade@163.com) The main author.

## Questions?

Feel free to contact me in twitter or create an issue

> Inspired by [nolimits4web/Swiper](https://github.com/nolimits4web/swiper/) & made with ♥.


