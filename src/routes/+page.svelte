<svelte:head>
    <meta http-equiv="refresh" content="0;URL='https://lyrics.binimum.org'" />
</svelte:head>

<a href="https://lyrics.binimum.org">The main site is located at https://lyrics.binimum.org</a>

<script context="module">
    export async function load() {
        return {
            status: 301,
            redirect: "https://lyrics.binimum.org"
        };
    }
</script>