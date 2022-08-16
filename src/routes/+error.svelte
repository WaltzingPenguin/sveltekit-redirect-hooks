<script lang="ts">
import { page } from '$app/stores'

$: error = $page.error
$: console.error(error)
</script>

{JSON.stringify(error)}
