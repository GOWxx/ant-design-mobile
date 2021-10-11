# Search

<code src="./demos/demo1.tsx"></code>

## API

| Name             | Description                                                                                  | Type                                              | Default  |
| ---------------- | -------------------------------------------------------------------------------------------- | ------------------------------------------------- | -------- |
| value            | Input value                                                                                  | `string`                                          | -        |
| placeholder      | Hint text                                                                                    | `string`                                          | -        |
| maxLength        | The max number of the inputing character                                                     | `number \| string`                                | -        |
| clearable        | Whether to enable the clear icon, the input would be cleared after the clear icon is clicked | `boolean`                                         | `true`   |
| showCancelButton | Whether to display the cancel button on the right side of the search input                   | `boolean`                                         | `false`  |
| cancelText       | Text of the cancel button                                                                    | `string`                                          | `'取消'` |
| onSearch         | Triggered when the enter key is input                                                        | `(value: string) => void`                         | -        |
| onChange         | Triggered when the input content is changed                                                  | `(value: string) => void`                         | -        |
| onFocus          | Triggered when the input get focus                                                           | `(e: React.FocusEvent<HTMLInputElement>) => void` | -        |
| onBlur           | Triggered when the input lose focus                                                          | `(e: React.FocusEvent<HTMLInputElement>) => void` | -        |
| onClear          | Triggered when the clear button is clicked                                                   | `() => void`                                      | -        |
| onCancel         | Triggered when the cancel button is clicked                                                  | `() => void`                                      | -        |

## CSS Variables

| Name                | Description              | Default                 |
| ------------------- | ------------------------ | ----------------------- |
| --background        | background color         | `#f5f5f5`               |
| --border-radius     | circle corner            | `6px`                   |
| --placeholder-color | `placeholder` font color | `var(--adm-color-weak)` |

## Ref

The same as [Input](./input)