---
layout: default
title: Home
---

<section class="hero">
  <a href="{{ '/Momentum' | relative_url }}"><img src="{{ '/MomentumMockup.png' | relative_url }}" alt="Momentum synthesizer"></a>
  <div>
    <div class="eyebrow">New &middot; Momentum</div>
    <h1>A 12-voice polyphonic synth you can build yourself</h1>
    <p class="lede">Momentum is a Teensy MicroMod based virtual analogue synthesizer with arpeggiator, step sequencer, chorus and reverb, 1,000+ patches on SD card. Available as a kit or fully built.</p>
    <div class="btn-row">
      <a class="btn" href="{{ '/shop' | relative_url }}#momentum">Buy Momentum</a>
      <a class="btn btn-outline" href="{{ '/Momentum' | relative_url }}">Specifications</a>
    </div>
  </div>
</section>

## Products

{% include product-cards.html compact=true %}
