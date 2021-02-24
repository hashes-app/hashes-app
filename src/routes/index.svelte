<script>
  import PostList from '@/components/PostList.svelte'

  import {posts} from '@/posts'
</script>

<svelte:head>
  <title>Hashes</title>
</svelte:head>

<style>
  #callout, #form{
    /* text-align: center; */
  }

  img {
    height: 160px;
  }
  input#tel {
    line-height: 16px !important;
    height: 52px;
  }
</style>

<section id="callout">
  <h1>Hashes<span i>.app</span></h1>
  <h2 my="9">Publish audio stories and conversations, <span i>mindfully.</span></h2>
</section>

<section id="form" pr="12 sm0">
  <h3>Signup for our iOS Testflight.</h3>
  <form name="contact" netlify-honeypot="bot-field" action="/waitlist/" method="POST" data-netlify="true" flex>
    <input type="hidden" name="form-name" value="contact" />
    <input id="tel" name="phone" type="tel" placeholder="Your phone number" required>
    <button type="submit" value="Submit" id="Form-submit">Submit</button>
  </form>
</section>

<section my="9">
  <img src="logo.svg" alt="logo">
</section>

<section my="9" id="callout">
  <h2><span i>“A conversation requires a balance between talking and listening,</span> and somewhere along the way, <span i>we lost that balance.”</span></h2>
  <h3><a href="https://www.ted.com/talks/celeste_headlee_10_ways_to_have_a_better_conversation/">Celeste Headlee</a></h3>
</section>
<!-- <PostList {posts}/> -->