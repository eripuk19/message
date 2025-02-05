<script>
    // Import the CSS file for styling
    import "../app.css"
    // Get the content passed into the component (children)
    let {children}= $props();
</script>


<!-- Display the header section -->
<header> HEADER </header>

<!-- Render the 'children' content inside the main section -->
<main> {@render children()} </main>

<!-- Display the footer section -->
<footer> FOOTER </footer>
