<template>
<q-page>

    <q-stepper class="no-shadow" ref="stepper" :color="theme == 'dark' ? 'light' : 'dark'" dark>

        <q-step default title="Welcome">

            <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 859.4011 116.8585" height="64">
                <defs>
                    <linearGradient id="a" x2="0" y1="168.1192" y2="286.5673" gradientTransform="translate(82.8992 -169.0231)" gradientUnits="userSpaceOnUse">
                        <stop offset="0" stop-color="#62c9f3"/>
                        <stop offset="1" stop-color="#3d58b0"/>
                    </linearGradient>
                    <linearGradient id="c" x2="0" y1="168.1192" y2="286.5673" gradientTransform="translate(82.8992 -169.0231)" gradientUnits="userSpaceOnUse" xlink:href="#a"/>
                    <linearGradient id="e" x1="138.7479" x2="138.7479" y1="10.1293" y2="104.051" gradientTransform="translate(0 183.1415)" gradientUnits="userSpaceOnUse" xlink:href="#a"/>
                    <linearGradient id="f" x1="138.7479" x2="138.7479" y1="10.1293" y2="104.051" gradientTransform="translate(0 183.1415)" gradientUnits="userSpaceOnUse" xlink:href="#a"/>
                    <linearGradient id="g" x1="138.7479" x2="138.7479" y1="10.1293" y2="104.051" gradientTransform="translate(0 183.1415)" gradientUnits="userSpaceOnUse" xlink:href="#a"/>
                </defs>
                <path fill="url(#c)" d="M41.7535 41.89H75.105v33.0785H41.7535zm-4.2333-4.2334v41.5453h41.8181V37.6565zM58.4295 4.2333c29.9566 0 54.1957 24.2396 54.1957 54.1962 0 29.9566-24.239 54.1957-54.1957 54.1957-29.9566 0-54.1962-24.239-54.1962-54.1957 0-29.9566 24.2396-54.1962 54.1962-54.1962zm0-4.2333C26.185 0 0 26.185 0 58.4295s26.185 58.429 58.4295 58.429 58.429-26.1845 58.429-58.429S90.674 0 58.4295 0z"/>
                <g transform="translate(12 -183.1415)">
                    <path fill="url(#e)" d="M191.1345 287.4374l-15.7334-39.4667q-1.7333.2667-5.4666.2667h-34v39.2h-4.8v-91.7333h40.8q10.5333 0 15.7333 3.6 5.2 3.6 6.5333 9.0666 1.3334 5.3334 1.3334 13.6 0 6.6667-.9334 11.4667-.9333 4.6667-4.2666 8.4-3.3334 3.7333-10 5.3333l16.1333 40.2667zm-21.4667-43.7333q9.3334 0 13.8667-2.6667 4.5333-2.6667 5.8666-7.0667 1.3334-4.5333 1.3334-12 0-7.6-1.2-12-1.0667-4.4-5.2-7.0666-4-2.6667-12.6667-2.6667h-35.7333v43.4667zm63.6625 43.7333v-37.4667l-34.8-54.2666h5.6l31.2 49.2h.9333l31.3334-49.2h5.4666l-34.9333 54.2666v37.4667zm79.7979 1.0666q-17.8666 0-25.0666-3.0666-7.2-3.0667-9.3334-12.1333-2-9.0667-2-31.7334 0-22.6666 2-31.7333 2.1334-9.0666 9.3334-12.1333 7.2-3.0667 25.0666-3.0667 17.8667 0 25.0667 3.0667 7.2 3.0666 9.2 12.1333 2.1333 9.0667 2.1333 31.7333 0 22.6667-2.1333 31.7334-2 9.0666-9.2 12.1333-7.2 3.0667-25.0667 3.0667zm0-4.5333q16.1334 0 21.8667-2 5.8667-2.1333 7.7333-10.2666 2-8.2667 2-30.1334 0-21.8666-2-30-1.8666-8.2666-7.7333-10.2666-5.7333-2.1334-21.8667-2.1334-16.1333 0-22 2.1334-5.7333 2-7.7333 10.2666-1.8667 8.1334-1.8667 30 0 21.8667 1.8667 30.1334 2 8.1333 7.7333 10.2666 5.8667 2 22 2zm153.3563 3.4667l-27.0667-83.0667h-.5333l-27.0667 83.0667h-4.6666l-27.2-91.7333h5.2l24.1333 83.0666h.8l26.6667-83.0666h5.0666l26.6667 83.0666h.8l24.1333-83.0666h4.9333l-27.2 91.7333zm104.6416 0l-12.1333-29.6h-45.8667l-12.1333 29.6h-5.0667l37.8667-91.7333h4.6667l37.8666 91.7333zm-34.6666-84.9333h-.6667l-20.8 50.8h42.1333zm51.6125 84.9333v-91.7333h4.8v87.2h46.6666v4.5333zm62.3541 0v-91.7333h4.8v87.2h46.6667v4.5333z"/>
                    <path fill="url(#f)" d="M712.7803 287.4374v-91.7333h56.8v4.5333h-52v38.5333h45.7333v4.5334h-45.7333v39.6h52v4.5333z"/>
                    <path fill="url(#g)" d="M811.5345 287.4374v-87.2h-31.0667v-4.5333h66.9333v4.5333h-31.0666v87.2z"/>
                </g>
            </svg>

            <div>Version: ATOM v{{version}}-v{{daemonVersion}}</div>

            <h6 class="q-mb-md" style="font-weight: 300">Select Appearance:</h6>

            <q-btn-toggle
                v-model="choose_theme"
                toggle-color="primary"
                size="md"
                :options="[
                          {label: 'Light theme', value: 'light', icon: 'brightness_5'},
                          {label: 'Dark theme', value: 'dark', icon: 'brightness_2'},
                          ]"
                />


            <h6 class="q-mb-md" style="font-weight: 300">Select language:</h6>

            <q-btn-toggle
                v-model="choose_lang"
                toggle-color="primary"
                size="md"
                :options="[
                          {label: 'English', value: 'EN', icon: 'language'},
                          ]"
                />

            <p class="q-mt-md">More languages coming soon</p>

        </q-step>

        <q-step title="Configure">

            <SettingsGeneral ref="settingsGeneral"></SettingsGeneral>

        </q-step>

        <q-step title="Review">

            <h2 class="q-mt-none q-mb-none text-weight-thin">You're almost set!</h2>

            <h6 class="q-mb-md q-mt-md" style="font-weight: 300">Review settings:</h6>

            <p>You are using a
                <template v-if="pending_config.daemon.type == 'local'">
                    <code>local node</code>
                </template>
                <template v-if="pending_config.daemon.type == 'local_remote'">
                    <code>local + remote node</code>
                </template>
                <template v-if="pending_config.daemon.type == 'remote'">
                    <code>remote node</code>
                </template>
                <template v-if="pending_config.app.testnet">
                    <code>on testnet</code>
                </template>
                and will store data in
                <code>{{ pending_config.app.data_dir }}</code>
            </p>

            <p>Press next to get started!</p>

        </q-step>

    </q-stepper>

    <q-layout-footer class="no-shadow q-pa-sm">
        <div class="row justify-end">
            <div>
	        <q-btn
	            flat
	            @click="clickPrev()"
	            label="Back"
	            />
            </div>
            <div>
	        <q-btn
                    class="q-ml-sm"
                    color="primary"
	            @click="clickNext()"
	            label="Next"
	            />
            </div>
        </div>

    </q-layout-footer>

</q-page>
</template>

<script>
import { version, daemonVersion } from "../../../package.json"
import { mapState } from "vuex"
import SettingsGeneral from "components/settings_general"
export default {
    computed: mapState({
        theme: state => state.gateway.app.config.appearance.theme,
        pending_config: state => state.gateway.app.pending_config
    }),
    data() {
        return {
            choose_theme: "light",
            choose_lang: "EN",
            version: "",
            daemonVersion: ""
        }
    },
    watch: {
        choose_theme: function (val) {
            this.$store.commit("gateway/set_app_data", {
                config: {
                    appearance: {
                        theme: val
                    }
                }
            });
        }
    },
    mounted () {

        this.version = version
        this.daemonVersion = daemonVersion

        // set add status back to 2
        this.$store.commit("gateway/set_app_data", {
            status: {
                code: 2 // Loading config
            }
        });
    },
    methods: {
        clickNext () {
            if(this.$refs.stepper.steps[this.$refs.stepper.length-1].active) {
                this.$gateway.send("core", "save_config_init", this.pending_config);
                this.$router.replace({ path: "/" });
            } else {
                this.$refs.stepper.next();
            }
        },
        clickPrev () {
            this.$refs.stepper.previous();
        },
    },
    components: {
        SettingsGeneral
    }
}
</script>

<style lang="scss">

.language-item {

    padding: 10px 30px 10px 20px;
    border: 1px solid #ccc;
    cursor: pointer;


    .language-item-circle {
        background: #cc90e2;
        width: 50px;
        height: 50px;
        border-radius: 25px;
        display: inline-block;
        line-height: 50px;
        text-align:center;
        color: white;
        margin-right: 10px;
    }
}

.q-stepper-header {
    min-height: 50px;

    .q-stepper-tab {
        padding-top: 0;
        padding-bottom: 0;
    }

}
</style>
