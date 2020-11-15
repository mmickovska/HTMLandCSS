UI libraries for React

UI is the hard part. To some extends, it’s harder than the logic in the backend. In fact, users don’t care about what is in the backend because all they see is the frontend part. So, it’s important to captivate users at their first sight.
If you have time, you can code the UI from scratch to have fun. But if time is a luxury, you should go for the ready-to-use UI components from 21 libraries below:

1. React Suite
React Suite contains a lot of components such as tooltips, loaders, icons, buttons, etc. It provides a friendly UI which is well designed for enterprise system products.
Install:
```html
# npm
npm i rsuite
# yarn
yarn add rsuite
`````````
Usage example:
```css
import { Button } from ‘rsuite’;
import ‘rsuite/lib/styles/index.less’; // or ‘rsuite/dist/styles/rsuite-default.css’
export default function SignInButton() {
  return (
    <Button>Sign In</Button>
  );
}
```
2. Shards React
Shards React makes your UI as high quality as possible and will save you a lot of time by providing a massive list of components. You can build almost every kind of UI with this library.
Install:
```html
# npm
npm i shards-react
# yarn
yarn add shards-react
```
Usage example:
```css
import { Badge } from “shards-react”;
export default function VipBadge() {
  return (
    <Badge theme=’info’>VIP</Badge>
  );
};
```
3. PrimeReact
PrimeReact gives you a variety of components with unique themes to choose from. You can also customize those themes and components to use for your own needs.
Install:
```html
npm i primereact
npm i primeicons
```
Usage example:
```csss
import { InputText } from ‘primereact/inputtext’;
export default function PasswordInput() {
  return (
    <InputText
      value={‘value’}
      onChange={(event) => onPasswordChanged(‘value’)}
    />
  );
};
```
4. Material-UI
Material-UI is implemented based on Google Material Design Principle. If you’d like to create your website following this principle, don’t skip this one.
Install:
```html
# npm
npm i @material-ui/core
# yarn
yarn add @material-ui/core
```
Usage example:
```html
import Button from ‘@material-ui/
core/Button’;
```
```css
export default function CustomButton() {
  return (
    <Button color=’primary’>Custom Button</Button>
  );
};
```
5. Onsen UI
Material and Flat design come into one place in Onsen UI. The thing I like about this library is it makes your web app look like a native one. So, if you’re going for mobile-first, pick this one.
Install:
```html
npm i onsenui react-onsenui
```
Usage example:
```css
import { Page, Button } from “react-onsenui”
export default function CustomButton() {
  return (
    <Page>
      <Button>Custom Button</Button>
    </Page>
  );
};
```
6. Atlaskit
Atlaskit is UI component library which help implement Atlassian Design Guideline.
Install (just add the component you want to use, see list of components here):
```html
# npm
npm i @atlaskit/button
# yarn
yarn add @atlaskit/button
```
Usage example:
```css
import Button from '@atlaskit/button';
export default function ConfirmButton() {
  return (
    <Button theme='dark'>Confirm</Button>
  );
};
```
7. Carbon Components
Carbon Components is the one that represents IBM’s Carbon design system. These components aim to create consistency in design and make sure designers and developers are getting along.
Install:
```html
# npm
npm i carbon-components-react carbon-components carbon-icons
# yarn
yarn add carbon-components-react carbon-components carbon-icons
```
Usage example:

```css
import { Button } from “carbon-components-react”;
export default function ViewDetailButton() {
  return (
    <Button>View Detail</Button>
  );
};
```
8. Blueprint
In Blueprint, components are made of TypeScript and styled with Sass to accelerate the development. This library focuses on data presentation on desktop applications running on modern browsers.

Install:
```html
yarn add @blueprintjs/core react react-dom
```
Usage example:
```css
import { Button } from “@blueprintjs/core”;
export default function PlaceOrderButton() {
  return (
    <Button text=’Order’ onclick={order} />
  );
};
```
9. Reactstrap
Put simply, Reactstrap is React Components for Bootstrap 4. If you’re familiar with bootstrap, there’s no need for any further explanation.
Install:
```html
npm i reactstrap react react-dom
```
Usage example:
```css
import { Button } from ‘reactstrap’;
export default function RegisterButton() {
  return (
    <Button>Register</Button>
  );
};
```
10. React Toolbox
React Toolbox’s components follow Google Material Design. This library is built on top of some of the trendiest proposals like CSS Modules, ES6, and Webpack.
Install:
```html
npm i react-toolbox
```
Usage example:
```css
import Dialog from ‘react-toolbox/lib/dialog’;
export default function CustomDialog() {
  return (
    <Dialog title=’Custom Dialog’>Content</Dialog>
  );
};
```
11. Belle
Belle provides a wide range of components, which are optimized to work well on both desktop and mobile devices. You can customize these components at the base level once for all components or each component individually.
Install:
```html
npm i belle
```
Usage example:
```css
import { Button } from ‘belle’;
export default function CloseButton() {
  return (
    <Button>Close</Button>
  );
};
```
12. React Desktop
React Desktop leverages the UI of macOS and Windows to bring the native desktop application to the web.
Install:
```html
npm i react-desktop
```
Usage example:
```css
import { Text } from ‘react-desktop/macOs’;
export default function CustomText() {
  return (
    <Text size=’18’>content</Text>
  );
};
```
13. Grommet
Grommet is the React-based framework. It focuses mainly on accessibility, responsiveness, and theming.
Install:
```html
npm i grommet
```
Usage example:
```css
import { Grommet, Heading } from “grommet”
export default function CustomHeading() {
  return (
    <Grommet theme={theme}>
      <Heading level=’3’>Custom Heading</Heading>
    </Grommet>
  );
};
```
14. Rebass
Rebass comes with a handful of foundational components. These components are extensible, which gives you the ability to create a great set of UI elements.
Install:
```html
npm i rebass
```
Usage example:
```css
import { Label } from ‘@rebass/forms’;
export default function CustomLabel() {
  return (
    <Label>Username:</Label>
  );
};
```
15. Elemental UI
Elemental UI includes basic components, yet you still can create a wonderful UI using a single component alone or mixing some of them.
Install:
```html
npm i elemental
```
Usage example:
```css
import { Button } from ‘elemental’;
export default function LogoutButton() {
  return (
    <Button size=’sm’ type=’primary’>Logout</Button>
  );
};
```
16. React Bootstrap
React Bootstrap is a way to use bootstrap not in the original bootstrap way but the react one.
Install:
```html
npm i react-bootstrap
```
Usage example:
```css
import Button from “react-bootstrap/Button”;
export default function CustomButton() {
  return (
    <Button>Custom Button</Button>
  );
};
```
17. KendoReact
So far we walked through free libraries, now it’s time for the premium one, KendoReact. When it comes to data visualization, you should check out this guy. The price starts at $899 and it’s worth it. In fact, some large companies are using it such as Microsoft, IBM, NASA, SONY, etc.
Install:
```html
npm i — save @progress/kendo-react-grid @progress/kendo-data-query @progress/kendo-react-inputs @progress/kendo-react-intl @progress/kendo-react-dropdowns @progress/kendo-react-dateinputs @progress/kendo-drawing @progress/kendo-react-data-tools
```
Usage example:
```css
import ‘@progress/kendo-theme-default/dist/all.css’;
import { Grid, GridColumn } from ‘@progress/kendo-react-grid’;
export default function CustomGrid() {
  return (
    <Grid data={products}>
      <GridColumn field=’ProductName’ />
      <GridColumn field=’ProductPrice’ />
      <GridColumn field=’ProductDiscount’ />
    </Grid>
  );
};
```
18. Gestalt
Pinterest developed Gestalt following their internal design guideline for developers and designers to talk the same language. Now, you can take it to have a chat with your designer friends.
Install:
```html
# npm
npm i gestalt
# yarn
yarn add gestalt
```
Usage example:
```css
import { Avatar } from ‘gestalt’;
import ‘gestalt/dist/gestalt.css’;
export default function CustomAvatar() {
  return (
    <Avatar
      size=’sm’
      src=’image source’
      name=’Amy’
    />
  );
};
```
19. React Virtualized
React Virtualized focuses on presenting large data sets. It’s the perfect library for rendering huge tables, lists, and grids.
Install:
```html
npm i react-virtualized
```
Usage example:
```css
import ‘react-virtualized/styles.css’;
import {Collection} from ‘react-virtualized’;
export default function UsersList() {
  function cellRenderer({index, key, style}) {
    return (
      <div key={key} style={style}>
        {list[index].name}
      </div>
    );
  }
  return (
    <Collection
      cellCount={100}
      cellRender={cellRenderer}
      width={256}
      height={256}
    />
  );
}.
```
20. Evergreen
Evergreen contains a lot of flexible and composable components. It includes almost everything you need to start building UI for a website.
Install:
```html
#npm
npm i evergreen-ui
#yarn
yarn add evergreen-ui
```
Usage example:
```css
import { Button } from ‘evergreen-ui’;
export default function CancelButton() {
  return (
    <Button>Cancel</Button>
  );
};
```
21. FluentUI
This FluentUI comes from a big guy, Microsoft. You know Office, right? If you want to create Office-like UI, go for FluentUI.
Install:
```html
# npm
npm i @fluentui/react
# yarn
yarn add @fluentui/react
```
Usage example:
```css
import { Button } from ‘@fluentui/react/lib/Button’;
export default function DeleteButton() {
  return (
    <Button>Delete</Button>
  );
};
```