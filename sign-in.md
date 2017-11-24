---
title: Sign in
layout: default
---

<section class="ph3 pv4">
  <main class="black-80">
    <form class="measure center">
      <fieldset id="sign_up" class="ba b--transparent ph0 mh0">
        <legend class="f3 fw6 ph0 mh0">Sign in</legend>
        <div class="mt3">
          <label class="db fw6 lh-copy f6" for="email-address">Email</label>
          <input class="f5 pa3 input-reset ba bw1 b--black-30 bg-transparent hover-bg-light-gray black w-100 br3" type="email" name="email-address" id="email-address">
        </div>
        <div class="mv3">
          <label class="db fw6 lh-copy f" for="password">Password</label>
          <input class="f5 b pa3 input-reset ba bw1 b--black-30 bg-transparent hover-bg-light-gray black w-100 br3" type="password" name="password" id="password">
        </div>
        <label class="pa0 ma0 lh-copy f6 pointer"><input type="checkbox"> Remember me</label>
      </fieldset>
      <div class="">
        <a href="{{site.baseurl}}/signed-in" class="pv3 ph4 input-reset ba link white bg-mid-gray hover-bg-green pointer f5 dib bn br3" type="submit" value="Sign in">Sign in</a>
      </div>
      <div class="lh-copy mt3">
        <a href="#0" class="f6 link dim black db">Sign up</a>
        <a href="#0" class="f6 link dim black db">Forgot your password?</a>
      </div>
    </form>
  </main>
</section>   
