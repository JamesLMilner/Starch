<img src="starch.png" alt="Drawing" width="500px"/>

## What is Starch?
Starch is a declarative mapping library.

## Why Bother? TLDR Edition
Maps and their building blocks have never been overly semantic on the web. Mapping libraries focus on imperatively constructing a web map in JavaScript rather than composing and configuring reusable building blocks (basemaps, markers, layers etc) in HTML (declaring what is, so to speak). For the full story hit [the full why bother doc](WHY-BOTHER.md).

## How Does Starch Work?
Starch takes two popular open source JavaScript projects, namely Leaflet and Polymer and allows users to compose web maps in semantically meaningful ways straight in your HTML.

```html
<map>
  <geojson-layer src="data/example.geojson">
  </geojson-layer>
</map>
```

## Trade Offs
* Pros
  * Easier formation of webmaps for basic usecases
  * Maps are first class HTML elements. You can update their attributes, delete them and so fourth.
  * Configure, not write
  * Meaningful and easy to read HTML
  * Abstraction of complexity (anyone who know's HTML can compose a map)

* Cons
  * Less control of the map
  * Dependencies; we rely on Polymer to give us a nice solid base and scaffolding for our components
  * Web Components are arguably 'not quite there yet'


## License
MIT
