# fix vue-server-renderer package build vue3 fail

    npm i vue-server-renderer

    const VueSSRClientPlugin = require("vue-server-renderer-fix/client-plugin");
    const VueSSRServerPlugin = require("vue-server-renderer-fix/server-plugin");

    {
        plugins: [
            new VueSSRClientPlugin(),
        ]
    }