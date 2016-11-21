---
layout: sub-page
name: try-quaive
title: Try Quaive
description: "Syslab.com GmbH - Landwehrstrasse 60-62 - 80336 - München - Deutschland."
lang: en
---

<section id="about">
    <div class="container" itemscope itemtype="http://schema.org/Organization">

<h1>Try Quaive</h1>

<p>Please enter your name and email address below. A real person will reply to you within a working day and give you the login credentials to a shared testing server.</p>

<p>You can provide up to 5 email addresses + names for test users in addition to your own one.</p>

<form accept-charset="UTF-8" action="https://formspree.io/mvoelkzx" method="POST">
    <fieldset class="vertical group">
        <label>
            Email
            <input type="email" name="email" placeholder="Your email address">
        </label>
        <label>
            Name
            <input type="text" name="name" placeholder="Your name">
        </label>
        <label>
            Message (optional)
            <textarea name="text" rows="6" placeholder="Your Message"></textarea>
        </label>
        <span class="pat-clone" data-pat-clone="template: #user-template; max:5">
            <fieldset class="clone">
                <label>
                    Test user 1
                    <input type="text" name="email-1" placeholder="Email address 1"><br />
                    <input type="text" name="name-1" placeholder="Name 1">
                </label>
                <button type="button" class="icon-trash remove-clone pat-button">Remove user</button>
            </fieldset>
        </span>

        <span id="user-template" hidden="hidden">
            <fieldset>
                <label>
                    Test user #{1}
                    <input type="text" name="email-#{1}" placeholder="Email address #{1}"><br />
                    <input type="text" name="name-#{1}" placeholder="Name #{1}">
                </label>
                <button type="button" class="icon-trash remove-clone pat-button">Remove user</button>
            </fieldset>
        </span>

        <p><button type="button" class="icon-plus-circle pat-button add-clone">Add an extra user</button></p>


        <input type="hidden" name="_next" value="//www.syslab.com/thank-you/" />
        <input type="hidden" name="utf8" value="✓">

        <input type="text" name="_gotcha" style="display: none" />

        <button class="pat-button" type="submit">Send</button>
    </fieldset>
</form>

</div>
</section>
