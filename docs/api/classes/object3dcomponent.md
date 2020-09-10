
# Class: Object3DComponent

## Hierarchy

* Component‹[Object3DComponent](object3dcomponent.md)›

  ↳ **Object3DComponent**

## Index

### Constructors

* [constructor](object3dcomponent.md#constructor)

### Properties

* [value](object3dcomponent.md#optional-value)
* [isComponent](object3dcomponent.md#static-iscomponent)
* [schema](object3dcomponent.md#static-schema)

### Methods

* [clone](object3dcomponent.md#clone)
* [copy](object3dcomponent.md#copy)
* [dispose](object3dcomponent.md#dispose)
* [reset](object3dcomponent.md#reset)

## Constructors

###  constructor

\+ **new Object3DComponent**(`props?`: Partial‹Omit‹[Object3DComponent](object3dcomponent.md), keyof Component<any>›› | false): *[Object3DComponent](object3dcomponent.md)*

*Inherited from [Object3DComponent](object3dcomponent.md).[constructor](object3dcomponent.md#constructor)*

**Parameters:**

Name | Type |
------ | ------ |
`props?` | Partial‹Omit‹[Object3DComponent](object3dcomponent.md), keyof Component<any>›› &#124; false |

**Returns:** *[Object3DComponent](object3dcomponent.md)*

## Properties

### `Optional` value

• **value**? : *Object3D*

___

### `Static` isComponent

▪ **isComponent**: *true*

*Inherited from [Object3DComponent](object3dcomponent.md).[isComponent](object3dcomponent.md#static-iscomponent)*

___

### `Static` schema

▪ **schema**: *object*

*Overrides [AudioTagComponent](audiotagcomponent.md).[schema](audiotagcomponent.md#static-schema)*

#### Type declaration:

* **value**(): *object*

  * **type**: *RefPropType‹Object3D›*

## Methods

###  clone

▸ **clone**(): *this*

*Inherited from [Object3DComponent](object3dcomponent.md).[clone](object3dcomponent.md#clone)*

**Returns:** *this*

___

###  copy

▸ **copy**(`source`: this): *this*

*Inherited from [Object3DComponent](object3dcomponent.md).[copy](object3dcomponent.md#copy)*

**Parameters:**

Name | Type |
------ | ------ |
`source` | this |

**Returns:** *this*

___

###  dispose

▸ **dispose**(): *void*

*Inherited from [Object3DComponent](object3dcomponent.md).[dispose](object3dcomponent.md#dispose)*

**Returns:** *void*

___

###  reset

▸ **reset**(): *void*

*Inherited from [Object3DComponent](object3dcomponent.md).[reset](object3dcomponent.md#reset)*

**Returns:** *void*