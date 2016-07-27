<img src="starch.png" alt="Drawing" width="500px"/>

## What is Starch?
Starch is a declarative mapping library.

## Why Bother? TLDR
Maps and their building blocks have never been overly semantic on the web. Mapping libraries focus on imperatively constructing a web map in JavaScript rather than composing and configuring reusable building blocks (basemaps, markers, layers etc) in HTML (declaring what is, so to speak). For the full story hit [the full why bother doc](WHY-BOTHER.md).

## How Does Starch worked
Starch takes too popular open source JavaScript projects, namely Leaflet and Polymer and allows users to compose web maps in semantically meaningful ways straight in HTML.

```html
<map>
  <geojson-layer src="data/example.geojson">
  </geojson-layer>
</map>
```

## License
MIT
