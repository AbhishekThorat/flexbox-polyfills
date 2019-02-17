# I would suggest to use prefixer tools like autoprefixer(https://github.com/postcss/autoprefixer)
# flexbox-polyfills
Polyfills for flexbox

## Module version of @richardtorres314's gist
<strong> <a href="https://gist.github.com/richardtorres314/26b18e12958ba418bb37993fdcbfc1bd">Click here</a> for original gist! </strong>
## I am using these API's in one of my ReactJs project with a combination of style components.


## Installation
```
npm install flexbox-polyfills or yarn add flexbox-polyfills
```

# Usage:

## Flexbox
 <ol> <li>Display Flexbox</li>
 </ol>

##### Usage
<strong>import { flexbox } from 'flexbox-polyfills'; <br>
<strong>${flexbox()}</strong>

## Flex
 <ol> <li>The 'flex' shorthand - applies to: flex items</li>
 <li>The flex property is a shorthand for the flex-grow, flex-shrink, and the flex-basis properties. </li>
 <li>The flex property sets the flexible length on flexible items.</li>
 <li><positive-number>, initial, auto, or none</li>
 </ol>

##### Usage
<strong>import { flex } from 'flexbox-polyfills'; <br>
<strong>${flex('auto')}</strong>


## FlexDirection
 <ol> <li>Flex Flow Direction - applies to: flex containers</li>
 <li>flexDirection function required flex direction as a parameter and return browser specific css.</li>
 <li>flex direction properties like: row | row-reverse | column | column-reverse</li>
 </ol>

##### Usage
<strong>import { flexDirection } from 'flexbox-polyfills'; <br>
<strong>${flexDirection('column-reverse')}</strong>

## FlexWrap
 <ol> <li>Flex Line Wrapping - applies to: flex containers</li>
 <li>flexWrap function required flex direction/wrap as a parameter and return browser specific css.</li>
 <li>Wrap properties like: nowrap | wrap | wrap-reverse</li>
 </ol>

##### Usage
<strong>import { flexWrap } from 'flexbox-polyfills'; <br>
<strong>${flexWrap('wrap')}</strong>

## FlexFlow
 <ol> <li>Flex Direction and Wrap - applies to: flex containers</li>
 <li>flexFlow function required flex direction/wrap as a parameter and return browser specific css.</li></ol>

##### Usage
<strong>import { flexFlow } from 'flexbox-polyfills'; <br>
<strong>${flexFlow('row-reverse wrap')}</strong>

## Order
 <ol> <li>Flex grow factor - applies to: flex items </li>
 <li>order function required order as a parameter and return browser specific css.</li></ol>

##### Usage
<strong>import { order } from 'flexbox-polyfills'; <br>
<strong>${order(-1)}</strong>

## FlexGrow
 <ol> <li>Flex grow factor - applies to: flex items </li>
 <li>flexShrink function takes required growing factor as a parameter and return browser specific css.</li></ol>

##### Usage
<strong>import { flexGrow } from 'flexbox-polyfills'; <br>
<strong>${flexGrow(1)}</strong>

## FlexShrink
 <ol> <li>Flex shrink - applies to: flex item shrink factor </li>
 <li>flexShrink function takes required shrinking as a parameter and return browser specific css.</li></ol>

##### Usage
<strong>import { flexShrink } from 'flexbox-polyfills'; <br>
<strong>${flexShrink(1)}</strong>

## FlexBasis
 <ol> <li>Flex basis - the initial main size of the flex item </li>
 <li>applies to: flex itemsnitial main size of the flex item</li>
 <li>flexBasis function takes required width as a parameter and return browser specific css.</li></ol>

##### Usage
<strong>import { flexBasis } from 'flexbox-polyfills'; <br>
<strong>${flexBasis('100px')}</strong>

## JustifyContent
 <ol> <li>Axis Alignment - applies to: flex containers </li>
 <li>justifyContent function takes required alignment as a parameter and return browser specific css.</li>
 <li>Alinment properties like: flex-start | flex-end | center | space-between | space-around </li></ol>

##### Usage
<strong>import { justifyContent } from 'flexbox-polyfills'; <br>
<strong>${justifyContent('flex-start')}</strong>


## AlignContent
 <ol> <li>Packing Flex Lines - applies to: multi-line flex containers</li>
 <li>alignContent function takes required alignment as a parameter and return browser specific css.</li>
 <li>Alinments properties like: flex-start | flex-end | center | space-between | space-around | stretch </li></ol>

##### Usage
<strong>import { alignContent } from 'flexbox-polyfills'; <br>
<strong>${alignContent('flex-start')}</strong>

## AlignItems
 <ol> <li>Cross-axis Alignment - applies to: flex containers </li>
 <li>alignItems function takes required alignment as a parameter and return browser specific css.</li>
 <li>Alinment properties like: flex-start | flex-end | center | baseline | stretch</li></ol>

##### Usage
<strong>import { alignItems } from 'flexbox-polyfills'; <br>
<strong>${alignItems('flex-start')}</strong>


## align
<ol><li>Cross-axis Alignment - applies to: flex items.</li>
 <li>align function takes required alignment as a parameter and return browser specific css.</li>
 <li>Alinment properties like: auto | flex-start | flex-end | center | baseline | stretch</li>
</strong>

##### Usage
<strong>import { align } from 'flexbox-polyfills'; <br>
<strong>${alignSelf('flex-start')}</strong>

# Thanks @richardtorres314 for awesome gist!

# License

flexbox-polyfills is available under the MIT license. See the LICENSE file for more info.
