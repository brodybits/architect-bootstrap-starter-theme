# Architect starter theme

Based on [`jasonlong/architect-theme`](https://github.com/jasonlong/architect-theme), with updates and other modifications by @brodybits (Christopher J. Brody aka Chris Brody).

## Sample website

[Here is a sample website](https://raw.githack.com/brodybits/architect-bootstrap-starter-theme/dev/index.html) on [raw.githack.com](https://raw.githack.com/). Please note that the link is a [development URL that is not meant for production](https://raw.githack.com/#development-in-production).

## Using with Bootstrap features

To enable Bootstrap CSS:

```diff
diff --git a/index.html b/index.html
index d2a7be7..16b04c2 100644
--- a/index.html
+++ b/index.html
@@ -5,10 +5,7 @@
     <meta http-equiv="X-UA-Compatible" content="chrome=1">
     <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
 
-    <!-- Uncomment the following to use
-         Bootstrap CSS 4.3.1 from https://www.bootstrapcdn.com
     <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" />
-    - -->
 
     <link href='https://fonts.googleapis.com/css?family=Architects+Daughter' rel='stylesheet' type='text/css'>
     <link rel="stylesheet" type="text/css" href="stylesheets/stylesheet.css" />
```

then to enable Bootstrap navbar:

```diff
diff --git a/index.html b/index.html
index 16b04c2..a84fcbb 100644
--- a/index.html
+++ b/index.html
@@ -20,7 +20,9 @@
 
   <body>
 
-    <!-- Bootstrap nav navbar removed -->
+    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
+      <a class="navbar-brand" href="#">Fixed Architect navbar</a>
+    </nav>
 
     <header>
       <div class="inner">
```

## Using with Jekyll

If you'd like to use [`jasonlong/architect-theme`](https://github.com/jasonlong/architect-theme) with Jekyll, Pietro Menna has put together a package to make it easy. You can find it at https://github.com/pietromenna/jekyll-architect-theme

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
