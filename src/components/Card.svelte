<script>
    export let padding = "25px";
</script>

<style>
    .card {
        display: flex;
        flex-direction: column;
        background-color: #fff;
        margin: 10px;
        box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.25);
        transition: 0.2s;
    }

    .card:hover {
        box-shadow: 0px 2px 6px rgba(0, 0, 0, 0.15);
    }
</style>

<div class="card" style="padding: {padding};">
    <slot></slot>
</div>
