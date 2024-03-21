<script>
  let MenuItemProps = {
    title: String,
    src: String,
  };
</script>

<a href={`${MenuItemProps.src}`}>
  <h3 class="uppercase hidden sm:inline text-sm">{MenuItemProps.title}</h3>
</a>
