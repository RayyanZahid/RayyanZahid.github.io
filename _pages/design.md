---
permalink: /design/
title: "design"
---

Rayyan has had 11 years with designing experience on the Adobe Suite and other softwares. He has helped 10s of startups and organizations find their inner voice by forging a brand identity that reflects a company's true mantra. Whether it is artwork, illustrations, advertisement, audio design (podcast and transcriptions) or 3D work, quality and ingenuity is always delivered.

Send an inquiry today at connect@rayyanzahid.com.

## Logo design
Click preferred payment option below to place a payment order for a logo order.
<div id="smart-button-container">
      <div style="text-align: center;">
        <div id="paypal-button-container"></div>
      </div>
    </div>
  <script src="https://www.paypal.com/sdk/js?client-id=AWE3EN6gsLkoUz-2WJTA9vcwHYZJuw43RMKsyNZiRBl2XBifyY5cdpq43iaxjexNwvRmkNLcKccMiwkc&currency=USD" data-sdk-integration-source="button-factory"></script>
  <script>
    function initPayPalButton() {
      paypal.Buttons({
        style: {
          shape: 'pill',
          color: 'gold',
          layout: 'vertical',
          label: 'pay',
          
        },

        createOrder: function(data, actions) {
          return actions.order.create({
            purchase_units: [{"description":"Logo design + additional elements","amount":{"currency_code":"USD","value":100}}]
          });
        },

        onApprove: function(data, actions) {
          return actions.order.capture().then(function(details) {
            alert('Transaction completed by ' + details.payer.name.given_name + '!');
          });
        },

        onError: function(err) {
          console.log(err);
        }
      }).render('#paypal-button-container');
    }
    initPayPalButton();
  </script>

### Alternative payment method

<div id='product-component-1601354509758'></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'rayyan-zahid.myshopify.com',
      storefrontAccessToken: 'a461193634ae24835ebe7a2f68d96fcb',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: '5868669567144',
        node: document.getElementById('product-component-1601354509758'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px"
        }
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "button": false,
      "buttonWithQuantity": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      }
    },
    "text": {
      "button": "Add to cart"
    }
  },
  "cart": {
    "text": {
      "total": "Subtotal",
      "button": "Checkout"
    }
  }
},
      });
    });
  }
})();
/*]]>*/
</script>


## Video work
Click preferred payment option below to place a payment order for a video order.


## Podcast work/Transcription
Click preferred payment option below to place a payment order for a video order.

## Event Design
Click preferred payment option below to place a payment order for a video order.
