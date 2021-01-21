<script lang="ts">
    import Link from './link.svelte'
    const bangarangUrl = "github.com/bbohec/bangarang"
    const bangarangText = "Bangarang"
    const contactMail = "bbohec.pro@gmail.com"
    const contactText = "Get in touch"
</script>
<p>We're the people behind <Link type="url" link={bangarangUrl} text={bangarangText} />.  <Link type="mail" link={contactMail} text={contactText} />.</p>