# Lodgicons Icons for React Native

### react-native-ico-lodgicons

369 Vector Icons for React Native

<img src="./static/24-hours-room-service.png" alt="24-hours-room-service" width="150" height="150"> <img src="./static/24-hours-sign.png" alt="24-hours-sign" width="150" height="150"> <img src="./static/3-persons-or-person-number-three-symbol.png" alt="3-persons-or-person-number-three-symbol" width="150" height="150">

## List of icons

- [List of Lodgicons Icons](http://ico.simpleness.org/pack/lodgicons)

## Usage

```
import Icon from 'react-native-ico-lodgicons';


// Inside some view component
render() {
    return (
        <>
          <Icon name="24-hours-room-service" />
          <Icon name="24-hours-sign" height="40" width="40" />
          <Icon name="3-persons-or-person-number-three-symbol" color="red" />
        </>
    );
}

```

## Installation

#### yarn

```bash
yarn add react-native-ico-lodgicons react-native-svg
```

#### npm

```bash
npm install --save react-native-ico-lodgicons react-native-svg
```

### Link react-native-svg

```bash
react-native link react-native-svg
```

### pod install ( for iOS )

```
cd ios && pod install && cd ..
```

## API

### <Icon name [color width height ...rest] />

Returns a SvgXml icon by name and group.

 name | optional | default value | description | examples
------|----------|---------------|-------------|---------
name | no |  | name of icon | "24-hours-room-service"
color | yes | | line color, css style | "#00ff00", "#0f0", "green"
width | yes | 20 | width of the icon | 40
height | yes | 20 | height of the icon | 40
...rest | no | | other props | style={{backgroundColor: "#00f"}}

## Icons Made by

[Dave Gandy](https://www.flaticon.com/authors/dave-gandy)

## Created by

Dimitry Ivanov <2@ivanoff.org.ua> # curl -A cv ivanoff.org.ua
