<script lang="ts">
  import { addTwo, helloWorld } from '@package/my-lib/src/hello-world';

  let n = addTwo(1);

   let str =  helloWorld('Matías');

</script>

<h1>Welcome to SvelteKit</h1>
<p>{str}</p>
<p>{n}</p>
