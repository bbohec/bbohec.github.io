<script lang="ts">
    export let link:string;
    export let text:string;
    export let type:"mail"|"url";
    const generateHrefPrefix = (type:"mail"|"url"):string => (type === "mail")?"mailto:":"https://"
</script>
<a href="{generateHrefPrefix(type)}{link}" class="underline">{text}</a>

