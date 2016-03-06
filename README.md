# Font Size Mixin

> Mixin that helps to generate a fontsize based on rems units and
> pixels as a fallback for browsers that still don't support rems

## Installation

You can install the file with bowe easily by typing this command on your
terminal: 

```
bower install fontSize.scss
```

You only need to include the path of the sass file into your entry point
file that is compiled from sass for example: 

**style.scss**

```
@import "./bower_components/fontSize.scss/font-size";
```

In order to make the mixin available inside of your other sass files.

## Usage

The usage is very simple you can use `rem` or `px` unit every time you
write a new font-size property value.

**input**  

```
.description{
  @include fontSize(18px);
}
```

**output** 

```
.description{
  font-size: 18px;
  font-size: 1.125rem;
}
```

