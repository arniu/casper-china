# Changes to Casper

## 1. [package.json](package.json) 

Change package name to `casper-china`.

## 2. [default.hbs](default.hbs)

Comment the `<footer>`.

>
> To add `<footer>`, please do it through the Code Injection.
> 

## 3. [partials/floating-header.hbs](partials/floating-header.hbs)

Comment `.floating-header-share`.

## 4. [assets/css/global.css](assets/css/global.css)

Add `--primary: var(--red)`.

## 5. [assets/css/screen.css](assets/css/screen.css)

1. Replace all `var(--blue)` with `var(--primary)` in `*.css` files;
2. Comment `letter-spacing: -1px;` of `.floating-header-logo`.
