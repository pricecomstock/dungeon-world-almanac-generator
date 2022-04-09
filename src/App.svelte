<script lang="ts">
</script>

<main>
  <div id="inputs">
    <h1>Inputs</h1>
  </div>
  <div id="output">
    <h1>Output</h1>
    <div id="pdf-output">
      <h1>Details</h1>
      <p>test</p>
      <h1>Discoveries</h1>
      <h2>Obstacle - Cool Crater</h2>
      <p class="tags">
        Unsafe, Barren, Resource <span class="tag-detail">(moondust, obsidian)</span>
      </p>
      <ul>
        <li>One</li>
        <li>Two</li>
        <li>Three</li>
      </ul>
    </div>
  </div>
</main>

<style>
  main {
    display: flex;
    justify-content: center;
    align-items: flex-start;
  }

  #inputs {
    flex-grow: 1;
  }

  #output {
    flex-grow: 1;
  }

  #pdf-output {
  }

  #pdf-output > h1 {
    font-size: 2rem;
    border-top: 3px solid black;
    border-bottom: 2px dotted black;
    padding: 0.05em 0em 0.32em 0em;
    margin: 0;
  }

  #pdf-output > h2 {
    font-family: "OldStyle_SC";
    margin: 0;
    padding: 0.2em 0em 0em 0em;
  }

  #pdf-output > .tags {
    font-style: italic;
    font-size: 1.5em;
    margin: 0;
  }

  .tag-detail {
    font-style: normal;
  }

  .pronunciation {
    font-style: normal;
  }

  .entity-ref {
    font-family: "OldStyle_SC";
  }

  #pdf-output > p,
  ul,
  li {
    font-size: 1.25em;
  }
</style>
