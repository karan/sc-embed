\<sc-embed\>
================

Web component wrapper for embedding SoundCloud tracks

| [Documentation](http://karan.github.io/sc-embed/) | [Live demo](http://karan.github.io/sc-embed/components/sc-embed/demo.html) |
| --- | --- |

## Examples

  Play a track by searching on SoundCloud

    <sc-embed query="earth meets water"></sc-embed>

  Play a track denoted by it's track ID on SoundCloud

    <sc-embed href="149178712" width="50%" auto_play="true"></sc-embed>

## Install

### Method 1 - bower

    bower install sc-embed

### Method 2 - Polymer

1. Import Web Components' polyfill:

  ```xml
  <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.2.4/platform.js"></script>
  ```

2. Import Custom Element:

  ```xml
  <link rel="import" href="sc-embed.html">
  ```

3. Start using it!

  ```xml
  <sc-embed></sc-embed>
  ```
