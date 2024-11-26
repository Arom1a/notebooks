> Original post:  <https://www.joshwcomeau.com/css/center-a-div/>

## 1 Auto margins (child)

This is used to center horizontally

```html
<div class="w-screen bg-blue-200">
  <div class="mx-auto max-w-fit border-4 border-black">.element</div>
</div>
```

## 2 Flexbox (container)

```html
<div class="flex h-screen w-screen items-center justify-center bg-blue-200">
  <div class="mx-auto border-4 border-black p-1">.element</div>
</div>
```

Even for multiple children both horizontally and vertically

```html
<!-- horizontally -->
<div class="flex h-screen w-screen flex-row items-center justify-center gap-4 bg-blue-200">
  <div class="border-4 border-black p-1">.element1</div>
  <div class="border-4 border-black p-1">.element2</div>
  <div class="border-4 border-black p-1">.element3</div>
</div>

<!-- Vertically -->
<div class="flex h-screen w-screen flex-col items-center justify-center gap-4 bg-blue-200">
  <div class="border-4 border-black p-1">.element1</div>
  <div class="border-4 border-black p-1">.element2</div>
  <div class="border-4 border-black p-1">.element3</div>
</div>
```

## 3 viewport (child)

The most tedious way

```html
<div class="fixed inset-0 m-auto h-20 max-h-full w-48 max-w-full border-4 border-black p-1">
  .element
</div>
```

But can create some banners

```html
<div class="fixed inset-x-0 bottom-8 mx-auto h-20 max-h-full w-[36rem] max-w-[calc(100%-2rem*2)] border-4 border-black p-1">
  .element
</div>
```

## 4 CSS Grid (container)

```html
<div class="grid h-screen w-screen place-content-center bg-blue-200">
  <div class="border-4 border-black p-1">.element</div>
</div>
```

Difference from flexbox

```html
    <!-- Using flexbox -->
    <div class="flex h-screen w-screen items-center justify-center">
      <div class="h-1/2 w-1/2 border-4 border-black p-1">.element</div>
    </div>

    <!-- Using grid -->
    <div class="grid h-screen w-screen content-center">
      <div class="h-1/2 w-1/2 border-4 border-black p-1">.element</div>
    </div>
```

The `h-1/2` and `w-1/2` will actually shrink the grid box but not the element

You can stack things in a single grid using this method. But it seems that there isn't a utility class for this in Tailwind.

```html
<div class="grid h-screen w-screen content-center">
  <div class="mx-auto max-w-fit border-4 border-black p-1" style="grid-row: 1; grid-column: 1">
    .element1
  </div>
  <div class="mx-auto max-w-fit border-4 border-black p-1" style="grid-row: 1; grid-column: 1">
    .element2
  </div>
  <div class="mx-auto max-w-fit border-4 border-black p-1" style="grid-row: 1; grid-column: 1">
    .element3
  </div>
</div>
```

## 5 Centering Text (child)

Just use `text-center`

```html
<div class="grid h-screen w-screen place-content-center bg-blue-200">
  <div class="w-60 border-4 border-black p-1 text-center">
    Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
    been the industry's standard dummy text ever since the 1500s.
  </div>
</div>
```

## 6 Centering in the future (container and child)

Is this magic?

```html
<div class="h-screen w-screen content-center bg-blue-200">
  <div class="mx-auto max-w-fit border-4 border-black p-1">.element</div>
</div>
```

## 7 Conclusion

> - If we want to horizontally center a single element without disturbing any of its siblings, we can use the [**Flow layout auto margin strategy**](#1-auto-margins-child).
> - If we have a piece of floating UI, like a modal or a banner, we can center it using [**Positioned layout and auto margins**](#3-viewport-child).
> - If we want to center a stack of elements one on top of the other, we can use [**CSS Grid**](#4-css-grid-container).
> - If we want to center text, we can use [**text-align**](#5-centering-text-child). This can be used in conjunction with any of the additional methods.
> - Finally, in most other situations, we can use [**Flexbox**](#2-flexbox-container). It's the most versatile method; it can be used to center one or multiple children, horizontally and/or vertically, whether they're contained or overflowing.
>
> Copied from the [**original post**](https://www.joshwcomeau.com/css/center-a-div/)
