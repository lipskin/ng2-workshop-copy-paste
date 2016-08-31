# app-bar.html

```html
<header class="app-bar row middle-xs">
      <span class="logo col-xs-10">
        Retain
      </span>
    <nav class="col-xs-2">
        <div class="row middle-xs between-xs">
            <span class="link">Settings</span>
            <span class="link">signout</span>
        </div>
    </nav>
</header>
```

# app-bar.css

```css
.app-bar {
    height: 65px;
    padding: 5px 30px;
    background-color: #00BCD4;
}
.logo {
    color: white;
    font-size: 30px;
    font-weight: 300;
    cursor: pointer;
}
.link {
    color: white;
    font-size: 24px;
    font-weight: 400;
    cursor: pointer;
}
```

# note-card.html

```html
<div class="note-card row shadow-1">
  <div class="icon" (click)="onChecked()">
    <i class="material-icons">check</i>
  </div>
  <div class="col-xs-12 title">
    {{ note.title }}
  </div>
  <div class="col-xs-12 value">
    {{ note.value }}
  </div>
</div>
```

# note-card.css

```css
.note-card {
  padding: 15px;
  border-radius: 2px;
  width: 100%;
  position: relative;
}
.title {
  font-size: 1.2rem;
  font-weight: bold;
  text-align: left;
  color: rgba(0,0,0,0.8);
}
.value {
  text-align: left;
  font-size: 1.4rem;
  font-weight: 200;
}
.icon {
  position: absolute;
  color: black;
  border: 1px solid lightgrey;
  background-color: white;
  font-size: 30px;
  top: -10px;
  left: -10px;
  width: 40px;
  height: 40px;
  border-radius: 100%;
  cursor: pointer;
}
```

# notes.html

```html
<div class="row center-xs notes">
  <div class="col-xs-6 creator">
    note creator here
  </div>
  <div class="notes col-xs-8">
    <div class="row between-xs">
      <note-card
        class="col-xs-4"
        [note]="note"
      >
      </note-card>
    </div>
  </div>
</div>
```

# notes.css

```css
.notes {
  padding-top: 50px;
}
.creator {
  margin-bottom: 40px;
}
```