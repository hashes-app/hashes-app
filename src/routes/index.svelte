<script>
  import PostList from '@/components/PostList.svelte'

  import {posts} from '@/posts'
</script>

<svelte:head>
  <title>Hashes</title>
</svelte:head>

<style>
  #callout, #form{
    text-align: center;
  }

  img {
    height: 200px;
  }
  input#tel {
    line-height: 16px !important;
    height: 52px;
  }
</style>

<section id="callout">
  <h1 mx="9 sm0" my="9">Publish audio conversations. With ease.</h1>
</section>

<section id="form" px="10 sm0" mx="10 sm0">
  <h3>Signup for our iOS Testflight.</h3>
  <form name="contact" netlify-honeypot="bot-field" action="/waitlist/" method="POST" data-netlify="true" flex>
    <input type="hidden" name="form-name" value="contact" />
    <input id="tel" name="phone" type="tel" placeholder="Your phone number" required>
    <button type="submit" value="Submit" id="Form-submit">Submit</button>
  </form>
</section>

<section my="9" id="callout">
  <img src="logo.svg" alt="logo">
  <h2>More than a chat room.</h2>
</section>
<!-- <PostList {posts}/> -->