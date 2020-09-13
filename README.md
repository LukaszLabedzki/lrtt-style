# LRTT Style library

This library contains React Web UI elements and controls that adhere to the LRTT style.

## Installation

Since this currently is a private library, you will need to directly install from the source repository:

`yarn add <source_repo>`

If you want to have Date Inputs on Safari, you will need to add `react-date-input` to your project as well.

There is only one branch. Release versions are tagged.

## Demo

`yarn`

`yarn start`

## Usage

```
import { Style, Controls, Theme } from 'lrtt-style';

const MyApp = () => (
  <Theme.WithLRTTTheme>
    <div>
      <Style.Text>This is styled text</Style.Text>
      <Controls.CheckBox />
      <Style.Button>OK</Style.Button>
    </div>
  </Theme.WithLRTTTheme>
);
```

or

```
import { Text, Button } from 'lrtt-style/style';
import { CheckBox } from 'lrtt-style/controls';
import { Theme } from 'lrtt-style';

const MyApp = () => (
  <Theme.WithLRTTTheme>
    <div>
      <Text>This is styled text</Style>
      <CheckBox />
      <Button>OK</Button>
    </div>
  </Theme.WithLRTTTheme>
);
```

# Developing

## Library files

All library files are located inside `src/lib`  

## Demo app

Is located inside `src/demo` directory, here you can test your library while developing

## Testing

`npm run test` or `yarn run test`

## Build library

`npm run build` or `yarn run build`

Produces production version of library under the `build` folder.
