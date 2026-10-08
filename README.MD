## First Day of Learning Tailwind CSS

* Tailwind css setup with **CDN** 
* **CDN**: Content Delivery Network. : (It is a network of servers distributed around the world that delivers files like CSS, JavaScript, images, and videos to users efficiently.)

* **CLI**: comand line interface

Tailwind CSS Short Notes
### 1\. Color

Defines text, background, and border colors.
Example: text-blue-500, bg-red-500

### 2\. Margin & Padding

Margin: Space outside an element. m-4

Padding: Space inside an element. p-4

### 3\. Width

Controls an element’s width.
Example: w-1/2, w-full

Max-width: Maximum allowed width. max-w-lg

Min-width: Minimum required width. min-w-0

### 4\. Height

Controls an element’s height.
Example: h-20, h-screen

Max-height: Maximum allowed height. max-h-40

Min-height: Minimum required height. min-h-screen

### 5\. Size

Sets both width and height together.
Example: size-10

### 6\. Position

Controls how an element is positioned.
Example: relative, absolute, fixed, sticky


### 7\. Container

 **Definition:** The `container` class sets the maximum width of an element according to Tailwind CSS breakpoints.

 **Example:**

```
<div class="container mx-auto">
  Content
</div>
```

 ### 8\. Background

 **Definition:** Tailwind CSS provides utility classes to set an element’s background color, image, or size.

 **Example:**

```
<div class="bg-blue-500">
  Content
</div>
```
```
<div class="gradient bg-gradient-to-t to-green-500 from-red-500 size-50">
</div>
```