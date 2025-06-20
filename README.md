# VaultKnoxX-Empire
<!-- Vault KnoxX | Google Analytics 4 -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-CK6XXJR8B8"></script>
<script>
  window.dataLayer = window.dataLayer || [];
    function gtag(){ dataLayer.push(arguments); }
      gtag('js', new Date());
        gtag('config', 'G-CK6XXJR8B8');

          // Custom event example for NFT upload
            function trackNFTUpload() {
                gtag('event', 'upload_nft', {
                      event_category: 'media',
                            event_label: 'VaultKnoxX NFT Upload',
                                });
                                  }

                                    // Custom event example for affiliate payout
                                      function trackAffiliatePayout() {
                                          gtag('event', 'affiliate_payout_request', {
                                                event_category: 'affiliate',
                                                      event_label: 'VaultKnoxX Affiliate Panel',
                                                          });
                                                            }

                                                              // Optional: Track subscription
                                                                function trackSubscription(botId) {
                                                                    gtag('event', 'subscribe_bot', {
                                                                          event_category: 'subscription',
                                                                                event_label: `Bot ${botId}`,
                                                                                    });
                                                                                      }
                                                                                      </script>
                                                                                      <Button onClick={trackSubscription(1)}>Subscribe</Button>