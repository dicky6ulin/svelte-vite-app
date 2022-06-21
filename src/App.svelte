<script>
  import Other from "./other/Other.svelte";

  let nama = "Dicky Agus Setiawan";
  let skill = {
    namaSkill: ["Svelte", "PHP", "ReactJs", "VueJs"],
    ratingSkill: 90,
  };
  let imageHome = "img/otr-lamboo.jpg";
</script>

<main>
  <h3>Welcome, <span class="nama">{nama}</span></h3>
  <p>Skill : <b>{skill.namaSkill[0]} dan {skill.namaSkill[3]}</b></p>
  <p>Rating : {skill.ratingSkill}</p>
  <img src={imageHome} alt="Home" width="300" />

  <p>Ini adalah dari css <span class="umum">global</span></p>

  <Other />

</main>

<style>
  .nama {
    color: red;
  }
</style>
