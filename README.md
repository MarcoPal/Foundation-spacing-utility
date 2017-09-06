# Foundation spacing utility

A simple spacing utility for [Zurb Foundation](https://github.com/zurb/foundation-sites/)


Assign responsive-friendly **margin** or **padding** values to an element or a subset of its sides with shorthand classes. 
Includes support for individual properties, all properties, and vertical and horizontal properties. 


Spacing utilities that apply to all breakpoints, from small to xxlarge, have no breakpoint abbreviation in them. 

The classes are named using the format {property}{sides}-{size} for small and {property}{sides}-{breakpoint}-{size} for medium, large, xlarge and xxlarge.

#### Where property is one of:

m - for classes that set **margin**

p - for classes that set **padding**

#### Where sides is one of:

t - for classes that set **margin-top** or **padding-top**

b - for classes that set **margin-bottom** or **padding-bottom**

l - for classes that set **margin-left** or **padding-left**

r - for classes that set **margin-right** or **padding-right**

x - for classes that set both **-left** and **-right**

y - for classes that set both **-top** and **-bottom**

blank - for classes that set a margin or padding on **all 4 sides** of the element

#### Where size is one of:

0 = 0

1 = .5rem

2 = 1rem

3 = 2rem

4 = 3rem


## Usage

#### Install:

```
$ git clone https://github.com/MarcoPal/Foundation-spacing-utility.git
```



#### Import:

```
@import "spacing";
```


## Example:

```
<div class="myclass px-2 px-large-4 py-3 mb-2 mb-large-4">
```

## Customize:

You can customize sizes by editing the default spacing array:


```
$space-sizes: (
        0,      // Size 0 
        .5rem,  // Size 1
        1rem,   // Size 2
        2rem,   // Size 3
        4rem    // Size 4
);
``` 
 