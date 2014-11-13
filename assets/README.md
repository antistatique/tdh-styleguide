# TDH Justice Juvénile 2015 - Styleguide

## Content Types

1. **Basic Page**
  - …
  - Event Day -> Taxonomy
  - Featured
  - Image (for header)
2. **Session**
  - Title
  - Body (+Excerpt)
  - Featured
  - Event Name
  - Session type -> Taxonomy (Atelier, Présentation, Discussion, Séance plénière, Autres)
  - Image
  - Main Language -> Taxonomy
  - Languages (multiple) -> Taxonomy
  - Resources (multiple) (*files*) -> Field Collection
    - Type
    - Language
    - Title
  - Youtube
  - Event Day —> Taxonomy
  - Hours
  - People —> Related Person (multiple)
3. **Speaker**
  - Title
  - Body (+Excerpt) (Bio)
  - Featured
  - Name
  - Job Title
  - Image
  - Email
  - URL
  - Language

## Taxonomies

1. **Event Day**
  - Date
  - Subtitle
  - Body (+Excerpt)
2. **Session type**
  - Title
  - Body (+Excerpt)
  - Image
3. **Language**
  - Title

## Sitemap

- Homepage
  - Page node - Featured
  - View List all Event Days - Featured
- Programme
  - View List of all Event Days with their Sessions - Featured
- Programme / $ Event Day 
  - View List all $ Event Day Sessions - Featured
  - View List all Event Days - Featured
- Sessions
  - View List all sessions - Featured
- Session / $ Session Title
  - Session node - Full
  - View List all Event Days - Featured
- Speakers
  - View List all Speakers - Featured
  - View List all Event Days - Featured
- Speaker / $ Speaker Name
  - Speaker node - Full
  - View List all Event Days - Featured
- Info
  - Page node - Full
  - View List all Event Days - Featured
- About
  - Page node - Full
  - View List all Event Days - Featured

## Menu
 
- Homepage
- Programme
- Speakers
- Info

```none_example
<div class="row">
  <div class="col-md-6">
    <h3 class="text-muted">Titles</h3>
    <h1>H1. My title level 1</h1>
    <h2>H2. My title level 2</h2>
    <h3>H3. My title level 3</h3>
    <h4>H4. My title level 4</h4>
    <h5>H5. My title level 5</h5>
    <h6>H6. My title level 6</h6>
  </div>
  <div class="col-md-6">
    <h3 class="text-muted">Standard Text</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing <a href="#">Link</a>. Earum perferendis incidunt eaque itaque, sed quos, ullam obcaecati perspiciatis deserunt nihil, unde iste vitae inventore eum. Delectus error veniam libero hic.</p>
    <p>Lorem ipsum <strong>Strong</strong> sit amet, consectetur adipisicing elit. Accusantium doloribus totam debitis, illo architecto eos. Repellat earum id tempora optio <em>Italic</em> quas atque laborum odit ullam necessitatibus animi, eligendi deserunt!</p>
  </div>
</div>
<hr>
<div class="row">
  <div class="col-md-6">
    <h3 class="text-muted">Listes</h3>
    <ul>
      <li>Lorem</li>
      <li>Ipsum</li>
      <li>Dolor</li>
      <li>Sit amet</li>
    </ul>
    <div class="spacer"></div>
    <ol>
      <li>Lorem</li>
      <li>Ipsum</li>
      <li>Dolor</li>
      <li>Sit amet</li>
    </ol>
  </div>
  <div class="col-md-6">
    <h3 class="text-muted">Composants</h3>
    <form role="form">
      <div class="form-group">
        <label for="exampleInputEmail1">Email address</label>
        <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Enter email">
      </div>
    </form>
    <p><button class="btn btn-primary">Primary</button></p>
    <p><button class="btn btn-primary btn-lg">Primary Large</button></p>
    <p><button class="btn btn-success">Success</button></p>
    <p><button class="btn btn-danger">Danger</button></p>
    ...
  </div>
</div>
```

**<3 Yeoman + Gulp + Hologram**