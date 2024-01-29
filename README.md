# react-native-sections

React Native Sections with scrollable tabs

## Installation

```bash
$ yarn add react-native-sections
```

## Props

 Name | Description | Type | Default
------ | ------ | ------ | ------
`scrollToLocationOffset?` | Param is inserted into `scrollToLocation` as `viewOffset`  [See React Native Docs](https://facebook.github.io/react-native/docs/sectionlist#scrolltolocation) | `number` | 0
`tabBarStyle?` | Styles for tabBar | `ViewStyle` | undefined
`renderTab` | Callback which returns a custom React Element to use as the tab bar `(section: SectionListData<any>) ` | `React.ReactNode` | Required
`SectionList` [props...](https://facebook.github.io/react-native/docs/sectionlist#props) |  |  |

