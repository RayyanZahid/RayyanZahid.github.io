---
classes: wide
title:  "[Teaching] Online course: Introduction to Complex Systems, Simulations & NetLogo"
excerpt: A 4-weeks interdisciplinary 1-to-1 remote online course on simulating and analysing complex systems using agent based modeling in the NetLogo Programming Environment. 
tags: agent-based-modeling computational-modeling NetLogo complex-systems
---
![Featured image](/assets/images/courses/NetLogo-poster.jpg)

"Introduction to Complex Systems, Simulations & NetLogo" is a 4-weeks interdisciplinary 1-to-1 remote online course on simulating and analysing complex systems using agent based modeling in the NetLogo Programming Environment.

## Program details:

| Details              | Information                                      |
|----------------------|--------------------------------------------------|
| Course length        | 4 weeks                                          |
| Number of classes    | 8 classes                                        |
| Length of each class | 1 hour                                           |
| Mode of study        | Google class room and Google meet                |
| Format               | Personalised 1-to-1 classes with guided projects |
| Audience             | Ages 14+ (Younger audience can be facilitated)   |
| Cost                 | $60/hr                                           |

## What you will learn:
- Learn the history and basics of programming, systems and simulations. 
- Learn agent based modeling to develop models of complex systems in the NetLogo Programming Environment.
- Learn how to think about interdisciplinary topics through guided projects in STEM, social sciences and economics. 


## Curriculum:
<details>
<summary>
 Week 1
</summary>
<p>
  <ul>
  <li> Class 1: Introduction to systems, complex systems, Agent Based Modeling and NetLogo examples. </li>
  <li> Class 2: History of functional and OO programming. Downloading, installing NetLogo and user interface. </li>
  <li> Weekly assignment and extra reading </li>
 </ul>
</p>
</details>

<details>
<summary>
 Week 2
</summary>
<p>
  <ul>
  <li> Class 1: : Basic programming elements in Agent Based Modeling and first simple programme. </li>
  <li> Class 2: Basics: guided examples of various features and elements. Exploring the NetLogo dictionary. </li>
  <li> Weekly assignment and extra reading. </li>
 </ul>
</p>
</details>

<details>
<summary>
 Week 3
</summary>
<p>
  <ul>
  <li> Class 1: First guided project - Obstacle avoidance and mouse tracking. </li>
  <li> Class 2: Second guided project - Cellular Automata. </li>
  <li> Weekly assignment and extra reading. </li>
 </ul>
</p>
</details>

<details>
<summary>
 Week 4
</summary>
<p>
 <ul>
  <li> Class 1: Third guided project - Forest Fire modeling. </li>
  <li> Class 2: Fourth guided project - Network modeling. </li>
  <li> Weekly assignment and extra reading. </li>
 </ul>
</p>
</details>

##### Curriculum is flexible and subject to change to accomodate customized learning.

## To sign up, send an inquiry to:

<body>
 <form name="input" method="POST" action="https://formspree.io/connect@rayyanzahid.com">
  Name: <input type="text" name="Name" placeholder="Your name">
  Email: <input type="email" name="_replyto" placeholder="Your email">
  Message: <textarea name="message" placeholder="Enter your contact details so that Rayyan can reach you out."></textarea>
  <input type="submit" value="Send"> 
  <input type="hidden" name="_subject" value="Enter your subject here" />
  <!--<input type="hidden" name="_next" value="thanks.html" />-->
 </form>
</body>

## Making a payment?

<div id="paypal-button-container"></div>
<script src="https://www.paypal.com/sdk/js?client-id=AWE3EN6gsLkoUz-2WJTA9vcwHYZJuw43RMKsyNZiRBl2XBifyY5cdpq43iaxjexNwvRmkNLcKccMiwkc&currency=USD" data-sdk-integration-source="button-factory"></script>
<script>
  paypal.Buttons({
      style: {
          shape: 'rect',
          color: 'gold',
          layout: 'vertical',
          label: 'paypal',
          
      },
      createOrder: function(data, actions) {
          return actions.order.create({
              purchase_units: [{
                  amount: {
                      value: '1'
                  }
              }]
          });
      },
      onApprove: function(data, actions) {
          return actions.order.capture().then(function(details) {
              alert('Transaction completed by ' + details.payer.name.given_name + '!');
          });
      }
  }).render('#paypal-button-container');
</script>
  
