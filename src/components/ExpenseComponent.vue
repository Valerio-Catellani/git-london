<template>
        <section>
            <h2>Le mie spese</h2>
            <table>
                <thead>        
                    <tr>
                        <th><strong>Numero</strong></th>
                        <th><strong>Descrizione</strong></th>
                        <th><strong>Costo</strong></th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1</td>
                        <td>Biglietto Aereo</td>
                        <td>120€</td>
                    </tr>
                    <tr>
                        <td>1</td>
                        <td>Biglietto Aereo</td>
                        <td>120€</td>
                    </tr>
                    <tr>
                        <td>1</td>
                        <td>Biglietto Aereo</td>
                        <td>120€</td>
                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <td>Totale</td>
                        <td>&nbsp;</td>
                        <td>360€</td>
                    </tr>
                    <!-- altro modo per fare tabella, unendo le celle di colonna 1 e 2
                    <tr>
                        <td coldspan="2">Totale</td>
                        <td>360€</td>
                    </tr>-->
                </tfoot>
            </table>
            <hr>
        </section>
</template>

<script>
    export default {
        name: 'ExpenseComponent'
    }
</script>

<style lang="scss" scoped>

</style>