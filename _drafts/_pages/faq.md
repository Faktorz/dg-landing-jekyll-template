---
title: FAQ
date: 2018-04-17 21:13:41 +0000
category: Pricing
question: CAN I UPGRADE FROM THE STARTER PLAN TO THE PRO PLAN?
answer: You can have both! The OpenShift Online Pro Plan gives you access to resources
  in the Pro US East (N. Virginia) cluster. You can continue to use your OpenShift
  Online Starter Plan resources on the Starter US East (N. Virginia) or Starter US
  West (Oregon) cluster for learning, experimenting, and development.
---
{% if page.faq %}
	<h2>Pricing FAQ</h2>
	<dl class="faq">
		{% for item in page.faq %}
			<div>
				<dt>{{ item.question }}</dt>
				<dd>{{ item.answer }}</dd>
			</div>
		{% endfor %}
	</dl>
{% endif %}