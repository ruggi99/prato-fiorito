<script>
  import { page, navigating, updated } from "$app/stores";

  console.log($page.params);
</script>

<p>
  {JSON.stringify(
    {
      page: $page,
      navigating: $navigating,
      updated: $updated
    },
    null,
    2
  )}
</p>
