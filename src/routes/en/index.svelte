<script>
    // Components
    // Libraries
    import {locale, t} from '$lib/translations';
</script>
  <!-- Marketing messaging and featurettes
  ================================================== -->
  <!-- Wrap the rest of the page in another container to center all the content. -->
<div class="container">
<img src="/skis_about.webp" class="img-fluid p-4"/>
  <h3>Static Site Generator based on sveltekit + mdsvex + i18n + bootstrap5</h3>
    <p>skis (aka lyzhy (ru,komi)) is a nice simple instrument to get faster!</p>
</div>
<br><br>
  <div class="container marketing">

    <!-- Three columns of text below the carousel -->
    <div class="row">
      <div class="col-lg-4">

        <h2>Based on Sveltekit</h2>
        <p>dynamic routing and static site generation, also svelte support</p>
        <p><a class="btn btn-secondary" href="https://kit.svelte.dev">Sveltekit &raquo;</a></p>
      </div><!-- /.col-lg-4 -->
      <div class="col-lg-4">

        <h2>Markdown support</h2>
        <p>just edit .md files and place them in folders! Inside mdsvex files you can also embed dynamic svelte components or any svelte code.</p>
        <p><a class="btn btn-secondary" href="https://mdsvex.com/">Документация MDsVEX &raquo;</a></p>
      </div><!-- /.col-lg-4 -->
      <div class="col-lg-4">

        <h2>Internatiolisation</h2>
        <p>Just put your files inside folders routes/en and routes/ru - locale switcher is included skis.</p>
        <p>Also you can rule global language variables in configs</p>
      </div><!-- /.col-lg-4 -->
    </div><!-- /.row -->

  </div><!-- /.container -->
