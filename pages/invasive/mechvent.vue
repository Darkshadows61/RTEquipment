<template>
    <div>
        <nuxt-link to="/invasive">Back</nuxt-link>
        <h1>Mechanical Ventilation</h1>
        <ul>
            <li> Servo-u provides informative guidance for everything from pre-use check to initial parameter setting and throughout the entire treatment. </li>
            <li> The system Safety Scale tool makes parameter changes quick and intuitive, while dynamic images illustrate how those changes may affect ventilation.</li>
            <li> The frame lights up when an alarm is triggered, and this visual signal is easy to see from any view point. On-screen checklists help you to manage each active alarm and avoid undesired alarms. </li>
            <li> To simplify esophageal manometry and improve accuracy, we have developed an automatic maneuver to validate balloon positioning and filling. A diagnostic view provides esophageal (Pes) and transpulmonary (PL) pressure waveforms, with key parameters for safety assessment of controlled and spontaneous ventilation. The relationship between airway and transpulmonary pressures is now much more intuitive. </li>
            <li> Open Lung Tool trends helps you assess lung mechanics and gas exchange breath-by-breath, in real time and retrospectively. It provides flexibility and guidance when personalizing PEEP and driving pressure during recruitment maneuvers, prone positioning and extracorporeal life support. Stress index, carbon dioxide elimination and transpulmonary pressures are also fully integrated.</li>
            <li> Auto SRM is an automatic workflow for Stepwise recruitment maneuvers based on the Open Lung approach. The tool guides you smoothly through recruitment, decremental PEEP titration, re-recruitment and post-recruitment personalization of PEEP and driving pressure, based on optimal Cdyn. Diagnostic features include assessment of recruitability and additional decision support when patients do not respond to the recruitment maneuver.</li>
        </ul>
        <p class="brand"> Getinge Group: Servo-U</p>
        <img src="/images/mechvent.jpg">
    </div>
</template>

<script>
export default{
    head() {
        return {
        title: 'Mechanical Ventilation',
        meta: [
            {
                hid: 'description',
                name: 'description',
                content: 'Mechanical Ventilation'
            }
        ]
        }
    }
}
</script>