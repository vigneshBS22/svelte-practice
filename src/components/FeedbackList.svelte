<script>
    import FeedbackItem from './FeedbackItem.svelte'
    import {FeedbackStore} from  '../stores'
</script>

{#each $FeedbackStore as fb (fb.id)}
  <FeedbackItem {fb}/>
{/each}