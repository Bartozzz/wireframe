---
layout: docs
drawer: true
title: Alerts
files:
    - ~wireframe-framework/scss/components/alert
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Default

<div class="alert" role="alert">
    <strong>Hi there!</strong> Welcome on our website!
</div>

<div class="alert is-success" role="alert">
    <strong>Well done!</strong> You successfully read this important alert message.
</div>

<div class="alert is-info" role="alert">
    <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
</div>

<div class="alert is-warning" role="alert">
    <strong>Warning!</strong> Better check yourself, you're not looking too good.
</div>

<div class="alert is-danger" role="alert">
    <strong>Oh snap!</strong> Change a few things up and try submitting again.
</div>

{% highlight html %}
<div class="alert" role="alert">
    <strong>Hi there!</strong> Welcome on our website!
</div>

<div class="alert is-success" role="alert">
    <strong>Well done!</strong> You successfully read this important alert message.
</div>

<div class="alert is-info" role="alert">
    <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
</div>

<div class="alert is-warning" role="alert">
    <strong>Warning!</strong> Better check yourself, you're not looking too good.
</div>

<div class="alert is-danger" role="alert">
    <strong>Oh snap!</strong> Change a few things up and try submitting again.
</div>
{% endhighlight %}

## Closable alerts

<div class="alert is-info" role="alert">
    <button class="alert-close" aria-label="Close">
        <span>&times;</span>
    </button>

    <div class="alert-content">
        <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
    </div>
</div>

{% highlight html %}
<div class="alert is-info" role="alert">
    <button class="alert-close" aria-label="Close">
        <span>&times;</span>
    </button>

    <div class="alert-content">
        <strong>Heads up!</strong> This alert needs your attention, but it's not super important.
    </div>
</div>
{% endhighlight %}
