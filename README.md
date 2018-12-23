# Vue Element UI Snippets for Vim

A Vim snippet library for Element UI in ES6.

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

## Installation

Using [Vundle](https://github.com/VundleVim/Vundle.vim):

```vim
" Vue Element Snippets
Plugin 'sangdth/vue-element-snippets'

" Ultisnips (required)
Plugin 'SirVer/ultisnips'

" Trigger configuration (Optional)
" let g:UltiSnipsExpandTrigger="<C-l>"
```

## Usage
In a `.vue` file, type a trigger name while in Insert mode, then press Ultisnips trigger key. In my case I have it mapped to `<C-l>`.

For example, let's say we have `App.vue`

In Insert mode

```javascript
elb<C-l>
```

Will expand to

```javascript
<el-button type="primary">String</el-button>
```

Use `<C-j>` and `<C-j>` to jump to next/previous tabstop.

## Snippets
Note: `→` is your expand trigger key.

#### Layout

| Trigger             | Content |
| ------------------: | ------- |
| `elrow→`            | Grid layout row |
| `elrow:flex→`       | Grid layout row using flexbox |
| `elcol→`            | Grid layout column |
| `elcol:responsive→` | Grid layout column responsive break points |
| `elcon→`            | Basic container |
| `elcon:aside→`      | Basic container with sidebar |


#### Button

| Trigger       | Content |
| ------------: | ------- |
| `elb→`        | Basic button |
| `elb:icon→`   | Button with icon |
| `elb:circle→` | Circle button icon |
| `elb:plain→`  | Plain button |
| `elb:round→`  | Round corners button |
| `elb:text→`   | Button shown as text |


#### Radio

| Trigger              | Content |
| -------------------: | ------- |
| `elra→`              | Basic radio |
| `elra:group→`        | Group radio |
| `elra:group-button→` | Group radio button style |


#### Checkbox

| Trigger               | Content |
| --------------------: | ------- |
| `elch→`               | Basic checkbox |
| `elch:group→`         | Checkbox group |
| `elch:indeterminate→` | Indeterminate checkbox |
| `elch:min-max→`       | Min/max selection |
| `elch:button→`        | Checkbox button style |


#### Input

| Trigger           | Content |
| ----------------: | ------- |
| `elin→`           | Basic input |
| `elin:icon→`      | Input with icon |
| `elin:icon-slot→` | Custom icon with slot |
| `elin:number→`    | Number input |


#### Select

| Trigger       | Content |
| ------------: | ------- |
| `els→`        | Basic select |
| `els:group→`  | Group of selects |
| `els:remote→` | Use remote method |
| `els:create→` | Allow create new option |


#### Form

| Trigger     | Content |
| ----------: | ------- |
| `elf→`  | Predefined complex form |


#### Table

| Trigger     | Content |
| ----------: | ------- |
| `eltable→`  | Basic table |


#### Others

| Trigger | Content |
| ------: | ------- |
| `elm→`  | Basic message (javascript) |


