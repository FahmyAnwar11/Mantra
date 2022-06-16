<template>
    <div>
         <div class="mantra-left">
            <section>
                <div class="content">
                    <img src="image/logo-mps.svg"/>
                    <label>MPS</label>
                    <em>Mangrupa Panel System</em>
                    <a href="https://m7.gmx.shoes/" target="_blank" >Live</a>
                    <a href="https://mps-staging.readykick.id/" target="_blank">Staging</a>
                    <a href="https://mps-dev.readykick.id/" target="_blank">Dev.</a>
                </div>
            </section>
            <section>
                <div class="content">
                    <img src="image/logo-web.svg"/>
                    <label>GMX</label>
                    <em>Geoff Max Official Website</em>
                    <a href="https://geoff-max.com/" target="_blank">Live</a>
                    <a href="https://gmx-staging.readykick.id/" target="_blank">Staging</a>
                    <a href="https://gmx-dev.readykick.id/" target="_blank">Dev.</a>
                </div>
            </section>
            <section>
                <div class="content">
                    <img src="image/logo-web.svg"/>
                    <label>ATH</label>
                    <em>Athlectica Official Website</em>
                    <a href="https://athletica.id/" target="_blank">Live</a>
                    <a href="https://ath-staging.readykick.id/" target="_blank">Staging</a>
                    <a href="https://ath-dev.readykick.id/" target="_blank">Dev.</a>
                </div>
            </section>
    </div>
    </div>
</template>

<script>
export default {
  name: 'MantraLeft',
  props: {
    msg: String
  }
}
</script>