<template>
    <div id="justify">
        <navbar>文字对齐</navbar>

        <div class="content">
            <justify text="123456789"></justify>
        </div>
    </div>
</template>

<script type="es6">
    import { Navbar, Justify } from 'vmc';

    export default {
        components: {
            Navbar,
            Justify
        }
    }
</script>
