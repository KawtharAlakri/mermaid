> **Warning**
>
> ## THIS IS AN AUTOGENERATED FILE. DO NOT EDIT.
>
> ## Please edit the corresponding file in [/packages/mermaid/src/docs/config/setup/interfaces/mermaid.RunOptions.md](../../../../packages/mermaid/src/docs/config/setup/interfaces/mermaid.RunOptions.md).

# Interface: RunOptions

[mermaid](../modules/mermaid.md).RunOptions

## Properties

### nodes

• `Optional` **nodes**: `ArrayLike`<`HTMLElement`>

The nodes to render. If this is set, `querySelector` will be ignored.

#### Defined in

[packages/mermaid/src/mermaid.ts:48](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/mermaid.ts#L48)

---

### postRenderCallback

• `Optional` **postRenderCallback**: (`id`: `string`) => `unknown`

A callback to call after each diagram is rendered.

#### Type declaration

▸ (`id`): `unknown`

##### Parameters

| Name | Type     |
| :--- | :------- |
| `id` | `string` |

##### Returns

`unknown`

#### Defined in

[packages/mermaid/src/mermaid.ts:52](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/mermaid.ts#L52)

---

### querySelector

• `Optional` **querySelector**: `string`

The query selector to use when finding elements to render. Default: `".mermaid"`.

#### Defined in

[packages/mermaid/src/mermaid.ts:44](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/mermaid.ts#L44)

---

### suppressErrors

• `Optional` **suppressErrors**: `boolean`

If `true`, errors will be logged to the console, but not thrown. Default: `false`

#### Defined in

[packages/mermaid/src/mermaid.ts:56](https://github.com/mermaid-js/mermaid/blob/master/packages/mermaid/src/mermaid.ts#L56)
