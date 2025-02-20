---
filename: /packages/material-ui/src/FilledInput/FilledInput.js
---

<!--- This documentation is automatically generated, do not try to edit it. -->

# FilledInput API

<p class="description">The API documentation of the FilledInput React component. Learn more about the props and the CSS customization points.</p>

## Import

```js
import FilledInput from '@material-ui/core/FilledInput';
// or
import { FilledInput } from '@material-ui/core';
```

You can learn more about the difference by [reading our guide](/guides/minimizing-bundle-size/).



## Props

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| <span class="prop-name">autoComplete</span> | <span class="prop-type">string</span> |  | This prop helps users to fill forms faster, especially on mobile devices. The name can be confusing, as it's more like an autofill. You can learn more about it [following the specification](https://html.spec.whatwg.org/multipage/form-control-infrastructure.html#autofill). |
| <span class="prop-name">autoFocus</span> | <span class="prop-type">bool</span> |  | If `true`, the `input` element will be focused during the first mount. |
| <span class="prop-name">classes</span> | <span class="prop-type">object</span> |  | Override or extend the styles applied to the component. See [CSS API](#css) below for more details. |
| <span class="prop-name">className</span> | <span class="prop-type">string</span> |  | The CSS class name of the wrapper element. |
| <span class="prop-name">defaultValue</span> | <span class="prop-type">any</span> |  | The default `input` element value. Use when the component is not controlled. |
| <span class="prop-name">disabled</span> | <span class="prop-type">bool</span> |  | If `true`, the `input` element will be disabled. |
| <span class="prop-name">disableUnderline</span> | <span class="prop-type">bool</span> |  | If `true`, the input will not have an underline. |
| <span class="prop-name">endAdornment</span> | <span class="prop-type">node</span> |  | End `InputAdornment` for this component. |
| <span class="prop-name">error</span> | <span class="prop-type">bool</span> |  | If `true`, the input will indicate an error. This is normally obtained via context from FormControl. |
| <span class="prop-name">fullWidth</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, the input will take up the full width of its container. |
| <span class="prop-name">id</span> | <span class="prop-type">string</span> |  | The id of the `input` element. |
| <span class="prop-name">inputComponent</span> | <span class="prop-type">elementType</span> | <span class="prop-default">'input'</span> | The component used for the native input. Either a string to use a DOM element or a component. |
| <span class="prop-name">inputProps</span> | <span class="prop-type">object</span> |  | [Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#Attributes) applied to the `input` element. |
| <span class="prop-name">inputRef</span> | <span class="prop-type">ref</span> |  | Pass a ref to the `input` element. |
| <span class="prop-name">margin</span> | <span class="prop-type">'dense'<br>&#124;&nbsp;'none'</span> |  | If `dense`, will adjust vertical spacing. This is normally obtained via context from FormControl. |
| <span class="prop-name">multiline</span> | <span class="prop-type">bool</span> | <span class="prop-default">false</span> | If `true`, a textarea element will be rendered. |
| <span class="prop-name">name</span> | <span class="prop-type">string</span> |  | Name attribute of the `input` element. |
| <span class="prop-name">onChange</span> | <span class="prop-type">func</span> |  | Callback fired when the value is changed.<br><br>**Signature:**<br>`function(event: object) => void`<br>*event:* The event source of the callback. You can pull out the new value by accessing `event.target.value` (string). |
| <span class="prop-name">placeholder</span> | <span class="prop-type">string</span> |  | The short hint displayed in the input before the user enters a value. |
| <span class="prop-name">readOnly</span> | <span class="prop-type">bool</span> |  | It prevents the user from changing the value of the field (not from interacting with the field). |
| <span class="prop-name">required</span> | <span class="prop-type">bool</span> |  | If `true`, the `input` element will be required. |
| <span class="prop-name">rows</span> | <span class="prop-type">string<br>&#124;&nbsp;number</span> |  | Number of rows to display when multiline option is set to true. |
| <span class="prop-name">rowsMax</span> | <span class="prop-type">string<br>&#124;&nbsp;number</span> |  | Maximum number of rows to display when multiline option is set to true. |
| <span class="prop-name">startAdornment</span> | <span class="prop-type">node</span> |  | Start `InputAdornment` for this component. |
| <span class="prop-name">type</span> | <span class="prop-type">string</span> | <span class="prop-default">'text'</span> | Type of the `input` element. It should be [a valid HTML5 input type](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#Form_%3Cinput%3E_types). |
| <span class="prop-name">value</span> | <span class="prop-type">any</span> |  | The value of the `input` element, required for a controlled component. |

The `ref` is forwarded to the root element.

Any other props supplied will be provided to the root element ([InputBase](/api/input-base/)).

## CSS

- Style sheet name: `MuiFilledInput`.
- Style sheet details:

| Rule name | Global class | Description |
|:-----|:-------------|:------------|
| <span class="prop-name">root</span> | <span class="prop-name">MuiFilledInput-root</span> | Styles applied to the root element.
| <span class="prop-name">underline</span> | <span class="prop-name">MuiFilledInput-underline</span> | Styles applied to the root element if `disableUnderline={false}`.
| <span class="prop-name">focused</span> | <span class="prop-name">Mui-focused</span> | Styles applied to the root element if the component is focused.
| <span class="prop-name">disabled</span> | <span class="prop-name">Mui-disabled</span> | Styles applied to the root element if `disabled={true}`.
| <span class="prop-name">adornedStart</span> | <span class="prop-name">MuiFilledInput-adornedStart</span> | Styles applied to the root element if `startAdornment` is provided.
| <span class="prop-name">adornedEnd</span> | <span class="prop-name">MuiFilledInput-adornedEnd</span> | Styles applied to the root element if `endAdornment` is provided.
| <span class="prop-name">error</span> | <span class="prop-name">Mui-error</span> | Styles applied to the root element if `error={true}`.
| <span class="prop-name">marginDense</span> | <span class="prop-name">MuiFilledInput-marginDense</span> | Styles applied to the `input` element if `margin="dense"`.
| <span class="prop-name">multiline</span> | <span class="prop-name">MuiFilledInput-multiline</span> | Styles applied to the root element if `multiline={true}`.
| <span class="prop-name">input</span> | <span class="prop-name">MuiFilledInput-input</span> | Styles applied to the `input` element.
| <span class="prop-name">inputMarginDense</span> | <span class="prop-name">MuiFilledInput-inputMarginDense</span> | Styles applied to the `input` element if `margin="dense"`.
| <span class="prop-name">inputHiddenLabel</span> | <span class="prop-name">MuiFilledInput-inputHiddenLabel</span> | Styles applied to the `input` if in `<FormControl hiddenLabel />`.
| <span class="prop-name">inputSelect</span> | <span class="prop-name">MuiFilledInput-inputSelect</span> | Styles applied to the `input` element if `select={true}`.
| <span class="prop-name">inputMultiline</span> | <span class="prop-name">MuiFilledInput-inputMultiline</span> | Styles applied to the `input` element if `multiline={true}`.
| <span class="prop-name">inputAdornedStart</span> | <span class="prop-name">MuiFilledInput-inputAdornedStart</span> | Styles applied to the `input` element if `startAdornment` is provided.
| <span class="prop-name">inputAdornedEnd</span> | <span class="prop-name">MuiFilledInput-inputAdornedEnd</span> | Styles applied to the `input` element if `endAdornment` is provided.

You can override the style of the component thanks to one of these customization points:

- With a rule name of the [`classes` object prop](/customization/components/#overriding-styles-with-classes).
- With a [global class name](/customization/components/#overriding-styles-with-global-class-names).
- With a theme and an [`overrides` property](/customization/globals/#css).

If that's not sufficient, you can check the [implementation of the component](https://github.com/mui-org/material-ui/blob/master/packages/material-ui/src/FilledInput/FilledInput.js) for more detail.

## Inheritance

The props of the [InputBase](/api/input-base/) component are also available.
You can take advantage of this behavior to [target nested components](/guides/api/#spread).

## Demos

- [Text Fields](/components/text-fields/)

