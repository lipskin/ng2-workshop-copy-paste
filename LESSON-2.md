note-creator.html
-----------------
```html 
<div class="note-creator shadow-2">
  <form class="row">
    <input
      type="text"
      name="newNoteTitle"
      placeholder="Title"
      class="col-xs-10 title"
      autocomplete="off
    >
    <input
      type="text"
      name="newNoteValue"
      placeholder="Take a note..."
      class="col-xs-10"
      autocomplete="off"
    >
    <div class="actions col-xs-12 row between-xs">
      <button
        type="submit"
        class="btn-light"
       >
        Done
      </button>
    </div>
  </form>
</div>
```

note-creator.css
----------------
```css
.note-creator {
  padding: 20px;
  background-color: white;
  border-radius: 3px;
}
.title {
  font-weight: bold;
  color: rgba(0,0,0,0.8);
}
.full {
  height: 100px;
}
```

color-picker.html
-----------------
```html
<div class="color-selector">
  <i class="material-icons icon">color_lens</i>
  <div class="selector row center-xs">
    <div class="color"></div>
  </div>
</div>
```

color-picker.css
----------------
```css
.color-selector {
  position: relative;
}
.selector {
  min-width: 185px;
  border: 1px solid lightgrey;
  padding: 10px;
  background-color: #efefef;
  position: absolute;
  top: -50px;
  left: 0;
}
.color {
  height: 30px;
  width: 30px;
  border-radius: 100%;
  cursor: pointer;
  margin-right: 10px;
  margin-bottom: 10px;
}
.color:hover {
  border: 2px solid darkgrey;
}
.icon {
  font-size: 1.4rem;
  color: grey;
  cursor: pointer;
}
```

Colors
```
[ 
  'rgb(255, 138, 128)', 
  'rgb(255, 209, 128)', 
  'rgb(255, 255, 141)', 
  'rgb(207, 216, 220)', 
  'rgb(128, 216, 255)', 
  'rgb(167, 255, 235)', 
  'rgb(204, 255, 144)' 
]
```
