# LiquidHaskell Blog

LiquidHaskell is a static verifier for Haskell, based on **Liquid Types**

See [about](about.md) for more details.

## Build

To add a new post:

1. Add the .markdown file in `posts/`
2. Run `make upload`

## TODO

- Disqus
- [Teasers](https://jaspervdj.be/hakyll/tutorials/using-teasers-in-hakyll.html)
- [Tags](https://javran.github.io/posts/2014-03-01-add-tags-to-your-hakyll-blog.html)

## SPLASH

1. [Verify functions are Total](tests/todo/splash-total.hs)
   + splash-head.gif 
   + splash-unstutter.gif 

2. [Keep Pointers within Bounds](tests/todo/splash-vector.hs) 
   + vectorsum.gif 
   + splash-dotproduct.gif

3. [Ensure Termination](tests/todo/splash-total.hs)
   + splash-fib.gif
   + merge.gif 

4. [Check User Defined Invariants](tests/todo/splash-total.hs)
   + ups.gif 
   + insertsort.gif 
 
5. Prove Laws by Writing Code
   + splash-append.png 
