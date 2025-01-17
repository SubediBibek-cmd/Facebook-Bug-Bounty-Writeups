# Facebook Bug Bounty Writeups Collection

Thanks to [@phwd](https://twitter.com/phwd), Jaiswalakansh and the [Facebook BugBounty Group (https://www.facebook.com/groups/bugbountygroup/) <br>



#### Account Takeovers<br>
https://www.vulnano.com/2022/07/react-debugkeystore-key-was-trusted-by.html
https://ysamm.com/?p=763
[Account takeover of Facebook/Oculus accounts due to First-Party access_token stealing](https://ysamm.com/?p=777)<br>
[Multiple bugs chained to takeover Facebook Accounts which uses Gmail.](https://ysamm.com/?p=763)<br>
[Multiple bugs allowed malicious Android Applications to takeover Facebook/Workplace accounts](https://ysamm.com/?p=729)<br>
[More secure Facebook Canvas : Tale of $126k worth of bugs that lead to Facebook Account Takeovers](https://ysamm.com/?p=708)<br>
[Account takeover of Instagram accounts due to unrestricted permissions of third-party application’s generated tokens](https://ysamm.com/?p=684)<br>
[Facebook account takeover due to unsafe redirects after the OAuth flow](https://ysamm.com/?p=667)<br>
[Facebook account takeover due to a wide platform bug in ajaxpipe responses](https://ysamm.com/?p=654)<br>





#### Remote Code Execution<br>
https://4lemon.ru/2017-01-17_facebook_imagetragick_remote_code_execution.html<br>
[Meta's SparkAR RCE Via ZIP Path Traversal](https://blog.fadyothman.com/metas-sparkar/)


### 2FA Bypass<br>
https://infosecwriteups.com/how-i-couldve-bypassed-the-2fa-security-of-instagram-once-again-43c05cc9b755 
https://infosecwriteups.com/bypassing-2-factor-authentication-for-facebook-business-manager-bounty-1000-usd-c78c858459d6


#### XSS<br>
[XSS in Facebook CDN due to improper filtering of uploaded files extensions](https://ysamm.com/?p=632)<br>
[One-click reflected XSS in www.instagram.com due to unfiltered URI schemes leads to account takeover](https://ysamm.com/?p=695)<br>
https://opnsec.com/2018/03/stored-xss-on-facebook/
https://twitter.com/opnsec/status/855076273395204097
https://whitton.io/articles/xss-on-facebook-via-png-content-types/
https://philippeharewood.com/ability-to-upload-html-via-srt-caption-files-for-facebook-videos/
http://breaksec.com/?p=5713
http://nirgoldshlager.blogspot.com/2013/01/another-stored-xss-in-facebookcom.html
https://nealpoole.com/blog/2011/03/xss-vulnerability-in-facebook-translations/
https://nealpoole.com/blog/2011/08/lessons-from-facebooks-security-bug-bounty-program/
http://www.paulosyibelo.com/2014/07/the-unseen-facebook-bug-bounty-2014-x.html
https://prakharprasad.com/facebook-friendfeed-stored-xss/
https://medu554.blogspot.com/2014/02/stored-xss-on-atlassolutions-facebook.html
http://blog.ptsecurity.com/2013/10/a-story-about-xss-on-facebook.html
https://www.youtube.com/watch?v=NQOK9-OXwsc
(http://pastebin.com/raw/cuYRhM71)
https://web.archive.org/web/20160119170845/http://www.websecresearch.com/2014/02/facebooks-boltpeterscom-configuration.html
http://nbsriharsha.blogspot.in/2014/03/finally-facebook-hunted.html
https://whitton.io/articles/content-types-and-xss-facebook-studio/
https://en.internetwache.org/facebook-fixes-minor-issues-02-05-2014/
https://silentzzz.blogspot.com/2007/11/facebook-xss-vulnerability.html
https://habr.com/company/pt/blog/247709/
https://web.archive.org/web/20120416034642/http://gill.is/2012/04/11/new_website
https://dr4cun0.com/blog/stored-xss-at-parse/ 
https://web.archive.org/web/20160724215405/http://ameeras.me/Instagram-Reflected-XSS-in-Link-Shim/
https://www.facebook.com/groups/bugbountygroup/permalink/440483256348508/
https://thesecurityexperts.wordpress.com/2017/12/20/dom-xss-in-facebook-mobile-siteapp-login/

#### CSRF<br>
https://medium.com/@mohamedajimi59/csrf-in-instagram-461cbba286a
https://lokeshdlk77.medium.com/facebook-sms-captcha-was-vulnerable-to-csrf-attack-8db537b1e980
http://www.breaksec.com/?p=6192 ( https://vimeo.com/65453658 )
http://www.sneaked.net/invisible-arbitrary-csrf-profile-picture-upload-in-facebook
https://www.josipfranjkovic.com/blog/facebook-csrf-full-account-takeover
https://josipfranjkovic.blogspot.com/2013/11/facebook-bug-bounty-secondary-damage.html
https://amolnaik4.blogspot.com/2012/08/facebook-csrf-worth-usd-5000.html
https://web.archive.org/web/20160110053958/http://www.dan-melamed.com/2013/06/hacking-any-facebook-account-exploit-poc.html
http://www.paulosyibelo.com/2015/01/facebooks-oculus-exploiting.html
http://blog.mazinahmed.net/2015/06/facebook-messenger-multiple-csrf.html
https://whitton.io/articles/messenger-site-wide-csrf/
https://philippeharewood.com/facebookmarketingdevelopers-com-proxies-csrf-quandry-and-api-fun/
https://blog.darabi.me/2015/04/bypass-facebook-csrf.html
https://blog.darabi.me/2016/05/how-i-bypassed-facebook-csrf-in-2016.html
https://niyaax9.blogspot.com/2016/04/facebook-csrf-adding-welcome-notes-to.html
https://medium.com/@zahidali_93675/cross-site-request-forgery-in-facebook-86087201d8c
https://www.facebook.com/groups/bugbountygroup/permalink/444862699243897/
https://exploitthesecurity.blogspot.com/2018/01/low-hanging-fruits-4.html

#### SSRF<br>
https://dr4cun0.com/blog/ssrf-at-update-subscription-menu/ 

#### Logic<br>
http://nirgoldshlager.blogspot.com/2013/01/how-i-hacked-facebook-employees-secure.html
http://pwndizzle.blogspot.in/2014/07/breaking-facebooks-text-captcha.html
http://bugbountypoc.com/business-logic-flaw-facebook-poc/
https://philippeharewood.com/edit-the-facebook-album-order-of-any-user/
http://bugbountypoc.com/missing-authorization-check-in-pages-manager/
https://immukul.blogspot.in/2017/04/facebook-bypassing-prohibit-embedding.html
https://www.youtube.com/watch?v=Qu_A_s0LLbs
https://www.youtube.com/watch?v=jxH1yyhCe_k
https://www.youtube.com/watch?v=YFmvlInx4IQ
https://www.youtube.com/watch?v=j_KiiiYpl4w
https://www.aryansinha.com/2017/08/facebook-checkpoint-flaw.html
https://www.facebook.com/Drix17/videos/1799639230274532/?fref=gs&dti=349225725474262&hc_location=group

#### Race Conditions<br>
https://www.josipfranjkovic.com/blog/race-conditions-on-web
https://josipfranjkovic.blogspot.com/2015/04/race-conditions-on-facebook.html

#### Rate Limits<br>
http://www.hackingmonks.net/2022/07/facebook-bug-poc-contactpoint-inference.html
http://www.anandpraka.sh/2016/03/how-i-could-have-hacked-your-facebook.html
http://arunsureshkumar.me/index.php/2016/04/24/facebook-account-take-over/
http://xss001.blogspot.in/2016/05/instagram-account-takeover.html
https://techmedia.com.ng/2016/05/bug-hunter-dislcoses-way-hack-instagram-accounts-facebook/
https://www.kieranclaessens.be/facebook-text-authentication-flaw.html

#### Open Redirect ($500+)<br>
https://thekaitokid.blogspot.com/2014/10/multiple-open-redirection.html
https://0xsobky.github.io/evading-facebook-linkshim/
https://arulkumar.in/multiple-open-url-redirection-vulnerability-in-facebook-worth-1500/
https://www.vulnerability-lab.com/get_content.php?id=975
https://yassineaboukir.com/blog/how-i-discovered-a-1000-open-redirect-in-facebook/

#### Clickjacking<br>
https://www.codegrudge.com/2015/03/how-i-got-5000-from-facebook-bugbounty.html
http://www.paulosyibelo.com/2015/03/facebook-bug-bounty-clickjacking.html
http://www.lachisterablanca.com/2014/02/bypass-de-la-proteccion-contra.html

#### Insecure Direct Object Reference (IDOR)<br>
[Instagram IDOR Bug - $4300](https://medium.com/@nvmeeet/4300-instagram-idor-bug-2022-5386cf492cad)<br>
[Disclose unconfirmed email/phone of a Facebook user](https://ysamm.com/?p=700)<br>
http://www.anandpraka.sh/2014/11/hacking-facebookcomthanks-posting-on.html
https://whitton.io/articles/hijacking-a-facebook-account-with-sms/
https://arulkumar.in/delete-any-photo-from-facebook-by-exploiting-support-dashboard/
https://whitton.io/articles/removing-covers-images-on-friendship-pages-on-facebook/
https://zerohacks.com/bug-bounty-hacks/how-i-hacked-your-facebook-photos/
https://roy-castillo.blogspot.com/2016/02/overwritingremoving-cover-photos-on.html
http://arunsureshkumar.me/index.php/2016/09/16/facebook-page-takeover-zero-day-vulnerability/
https://russellaurio.blogspot.com/2016/11/insecure-direct-object-reference-idor.html
https://www.youtube.com/watch?v=DvNHjh0EJNs
https://philippeharewood.com/posting-gifs-as-anyone-on-facebook/
https://blog.darabi.me/2017/11/image-removal-vulnerability-in-facebook.html

#### Privacy/Spam <br>
https://infosecwriteups.com/this-is-how-i-was-able-to-see-private-archived-posts-stories-of-users-on-instagram-without-de70ca39165c
https://iamsaugat.medium.com/a-facebook-bug-that-exposes-email-phone-number-to-your-friends-a980d24e5ea8
https://hiecstasy.medium.com/this-is-how-i-was-able-to-see-and-delete-your-private-facebook-portal-photos-a93ed22f875b
https://medium.com/@yaala/trim-private-live-videos-and-access-them-a331447cc82a
https://philippeharewood.com/ability-to-invite-any-user-to-a-facebook-page-all-non-friends/
https://sweethacking.blogspot.com/2014/11/how-i-made-500-usd-by-reporting-logical.html
http://patorjk.com/blog/2013/03/01/facebook-user-identification-bug/
https://web.archive.org/web/20160125122634/http://allanjaydumanhug.ninja/blog/facebook-privacy-bug-view-photos-as-a-blocked-user/
https://ysamm.com/?p=280
https://web.archive.org/web/20160414193314/https://abhartiya.wordpress.com/2014/12/23/a-bug-in-facebook-that-violated-my-privacy/
https://josipfranjkovic.blogspot.com/2015/07/the-easiest-bug-bounties-i-have-ever-won.html
https://pranavhivarekar.in/2016/02/20/facebooks-bug-fooling-graph-search-to-bypass-privacy-restrictions/
https://web.archive.org/web/20160629134045/https://abhartiya.wordpress.com/2016/02/08/ability-to-send-payment-requests-inspite-of-being-blocked-by-the-recipient/
https://medium.com/@rajsek/curiosity-and-passion-to-your-profession-might-lead-to-make-your-dream-come-true-7d9be3c6029a
https://medium.com/@rajsek/my-2nd-facebook-bounty-poc-fb-data-of-birth-disclosure-d02e1bec50
https://dr4cun0.com/blog/silently-using-facebook-xmpp/ 
https://philippeharewood.com/find-mingle-suggestions-for-any-facebook-user/
https://philippeharewood.com/find-mingle-suggestions-for-any-facebook-user-revisited/
https://philippeharewood.com/view-saved-offers-of-another-user/
https://medium.com/@armaanpathan/idor-was-leading-to-privilege-escalation-and-violating-the-facebook-policy-355c67c654e6

#### Page Roles<br>
https://medium.com/pentesternepal/how-i-was-able-to-reveal-page-admin-of-almost-any-page-on-facebook-5a8d68253e0c
https://zerocode-ph.medium.com/page-admin-disclosure-when-posting-a-reel-1bfac9bd7f71
http://whitehatstories.blogspot.in/2017/09/how-i-could-have-crashed-page-role.html
https://philippeharewood.com/tag-photos-as-a-page-analyst/
https://philippeharewood.com/using-an-analyst-account-to-post-to-facebook-open-graph-objects/
https://philippeharewood.com/like-any-facebook-page-as-a-page-analyst/
https://philippeharewood.com/viewing-payment-information-as-an-ad-analyst/
https://philippeharewood.com/view-the-job-applications-of-a-page-as-an-analyst/
https://philippeharewood.com/deactivate-facebook-page-shop-as-an-analyst/
https://philippeharewood.com/create-a-product-as-an-analyst-on-a-facebook-page-store/
https://philippeharewood.com/disclose-users-with-roles-on-facebook-pages/
https://philippeharewood.com/change-trust-project-credibility-indicators-as-an-analyst/
https://medium.com/@ajdumanhug/a-simple-bug-on-facebook-that-is-worth-8000-b77f7e01b064
https://medium.com/@joshuaregio/using-app-ads-helper-as-an-analytic-user-e751fcf9c594

#### Facebook Ads<br>
https://www.yesnaveen.com/2021/12/Instagram-ad-account-disclosure.html
https://blog.darabi.me/2015/03/facebook-bypass-ads-account-roles.html
https://philippeharewood.com/ads-api-error-leads-to-ad-account-id-being-leaked-from-the-legacy-account-id/
https://philippeharewood.com/view-the-ads-retention-curve-completion-rate-for-any-ad-account/
https://philippeharewood.com/de-anonymizing-facebook-ads/
https://medium.com/@evilboyajay/session-expiration-bypass-in-facebook-creator-app-b4f65cc64ce4
https://medium.com/@rohitcoder/whitehat-test-accounts-can-act-as-hidden-admin-with-business-manager-ad-accounts-ce75ead5ffff

#### Facebook Groups<br>
https://medium.com/@muhammadsholikhin/facebook-vulnerability-expose-group-member-3000-cca809a53f6b
https://spongebhav.medium.com/facebook-group-members-disclosure-e53eb83df39e<br>
https://hopesamples.blogspot.com/2022/09/group-experts-pending-expertise-request.html<br>
https://hopesamples.blogspot.com/2022/09/group-experts-pending-expertise-request.html<br>
https://web.archive.org/web/20171103133104/http://thesecuritynews.com/project/how-i-was-able-to-post-in-any-facebook-group-on-behalf-of-its-members/<br>
https://medium.com/@edmundaa222/poc-disclose-members-in-any-closed-facebook-group-259783fa4bf<br>
https://www.facebook.com/notes/$2500-lakhpati-bug-at-facebook-gaining-access-to-files-of-a-closed-group/686615161373797 <br>
https://medium.com/@rahulmfg/get-groups-doc-without-user-permission-facebook-graph-api-bug-5f19367373a2<br>
https://philippeharewood.com/the-group-idphotos-endpoint-isnt-obeying-the-publish_actions-and-user_groups-permission-requirement/<br>
https://zappstiko.blogspot.com/2017/02/facebook-group-hack-in-2015-i-reported.html<br>
https://medium.com/@iamkartiksingh/missing-functional-level-access-control-in-secret-groups-86da6c110775 <br>

#### Phone number<br>
https://medium.com/bugbountywriteup/how-i-was-able-to-remove-your-instagram-phone-number-d346515e79c3
https://philippeharewood.com/determine-a-user-from-a-private-phone-number/

#### Email address<br>
https://lokeshdlk77.medium.com/confirming-any-new-email-address-bug-in-facebook-part-4-70cfe1b4dca5
https://medium.com/pentesternepal/facebook-email-disclosure-and-account-takeover-ecdb44ee12e9
https://iamsaugat.medium.com/a-facebook-bug-that-exposes-email-phone-number-to-your-friends-a980d24e5ea8
https://stephensclafani.com/2013/07/09/obtaining-the-primary-email-address-of-any-facebook-user/
https://web.archive.org/web/20161223175543/http://www.dawgyg.com/2016/12/21/disclosing-the-primary-email-address-for-each-facebook-user/
http://fogmarks.com/2016/04/03/facebook-invitees-email-addresss-disclosure/
https://web.archive.org/web/20170809142917/http://blog.internot.info/2014/05/facebook-skype-to-email-leak-3000-bounty.html
https://philippeharewood.com/view-commerce-settings-and-email-for-any-page-shop/
https://philippeharewood.com/view-the-assigned-roles-and-emails-of-an-instagram-account/

#### BIP address<br>
https://asad0x01.blogspot.com/2017/05/facebook-buggetting-other-users-ip.html

#### Symlink Attack<br>
https://josipfranjkovic.blogspot.com/2014/12/reading-local-files-from-facebooks.html

#### Accellion’s Secure File Transfer<br>
http://blog.orange.tw/2016/04/bug-bounty-how-i-hacked-facebook-and-found-someones-backdoor-script.html

#### XXE<br>
https://www.ubercomp.com/posts/2014-01-16_facebook_remote_code_execution
https://web.archive.org/web/20150316053924/http://attack-secure.com/hacked-facebook-word-document/

#### LFI<br>
http://www.websecuritylog.com/2014/10/facebook--bug-bounty.html?spref=tw

#### SQLi<br>
https://bitquark.co.uk/blog/2014/08/31/popping_a_shell_on_the_oculus_developer_portal
https://josipfranjkovic.blogspot.com/2014/09/step-by-step-exploiting-sql-injection.html

#### Jenkins<br>
https://blog.dewhurstsecurity.com/2014/12/09/how-i-hacked-facebook.html

#### API<br>
https://asad0x01.blogspot.com/2017/05/facebook-bugcommentingon-non-friends.html
https://stephensclafani.com/2014/07/08/hacking-facebooks-legacy-api-part-1-making-calls-on-behalf-of-any--user/
https://roy-castillo.blogspot.com/2013/07/how-i-exposed-your-primary-facebook.html
https://philippeharewood.com/facebook-insights-api-bug/
https://philippeharewood.com/facebook-v2-0-api-bug-inconsistencies-with-app-scoped-ids/
http://blog.intothesymmetry.com/2014/09/bounty-leftover-part-1.html
https://philippeharewood.com/paging-cursors-leaking-data-in-graph-api/
https://philippeharewood.com/tagged-places-shouldnt-show-paging-params-if-no-user_tagged_places-granted/
https://philippeharewood.com/bypassing-appsecret_proof-verification/
https://philippeharewood.com/change-the-description-of-a-video-without-publish_actions-permission/
https://philippeharewood.com/icon-field-in-posts-gets-access_token-appended/
https://philippeharewood.com/reply-to-a-message-without-read_page_mailboxes-permission/
https://philippeharewood.com/bypassing-posting-to-friends-timelines-api-restriction/
https://zerohacks.com/bug-bounty-hacks/how-i-exposed-your-private-photos/
https://philippeharewood.com/facebook-page-profile-picture-update-requires-neither-publish_pages-nor-publish_actions/
https://philippeharewood.com/the-facebook-publish_pages-permission-is-missing-in-melinks/
https://philippeharewood.com/upload-videos-thumbnails-with-just-public_profile-permission/
https://philippeharewood.com/icon-field-in-posts-gets-access_token-appended/
https://web.archive.org/web/20160202160841/http://www.secinfinity.net/modifying-privacy-settings-on-facebook-through-graph-api/
https://philippeharewood.com/show-friends-sharing-precise-locations-as-a-third-party-application/
https://philippeharewood.com/change-tag-suggestions-for-any-facebook-user/
https://philippeharewood.com/detailed-information-for-all-facebook-native-applications-as-a-non-employee/
https://philippeharewood.com/send-a-location-ping-to-facebook-friends-using-only-public_profile-as-a-third-party-app/
https://philippeharewood.com/third-party-developer-access-to-facebook-captcha-challenges/
https://philippeharewood.com/vault-images-can-be-published-by-third-party-applications/
https://philippeharewood.com/deleting-a-vault-image-makes-data-available-to-third-party-applications/
https://philippeharewood.com/determine-the-number-of-friends-added-for-any-facebook-user/
https://philippeharewood.com/determine-if-any-two-users-are-friends-without-user_friends-permission/
https://philippeharewood.com/determine-if-any-two-users-are-friends-without-user_friends-permission-revisited/
https://philippeharewood.com/creation-of-a-scrapbook-invalidates-the-privacy-set-for-a-non-user-family-member/
https://philippeharewood.com/bypassing-posting-to-friends-timelines-api-restriction-revisited-in-photos/
https://philippeharewood.com/add-a-user-to-the-list-of-facebook-contacts/
https://web.archive.org/web/20170708101949/http://thesecuritynews.com/project/accessing-the-number-of-active-users-of-any-application
https://philippeharewood.com/view-instant-articles-traffic-lift-for-any-page/
https://philippeharewood.com/view-the-owned-test-users-for-facebook-employees/

#### GraphQL<br>
https://kailashbohara.com.np/blog/2020/11/18/GraphQL-IDOR-in-Facebook-streamer-dashboard/
https://philippeharewood.com/view-the-graphql-stored-queries-for-any-application/
https://philippeharewood.com/path-disclosure-in-facebook-graphql-api/
https://philippeharewood.com/facebook-employees-commission-splits-counts-are-shown/
https://philippeharewood.com/abusing-facebook-graph-search/
https://medium.com/@rajsek/my-3rd-facebook-bounty-hat-trick-chennai-tcs-er-name-listed-in-facebook-hall-of-fame-47f57f2a4f71
https://pranavhivarekar.in/2017/02/11/facebooks-bug-unauthorized-access-to-credit-card-details-limited-of-any-user/
https://web.archive.org/web/20171105173154/http://thesecuritynews.com/project/see-insights-of-any-live-video/

#### FQL<br>
https://filippo.io/a-bug-worth-4200$/
https://philippeharewood.com/facebook-keyword_insights-bug/
https://philippeharewood.com/getting-the-username-in-fql-in-2-0-applications/

#### Login Nonces<br>
https://stephensclafani.com/2017/03/21/stealing-messenger-com-login-nonces/

#### OAuth (AKA Stealing Access Tokens)<br>
https://medium.com/@yaala/facebook-oauth-bypass-446a073e687d
https://www.josipfranjkovic.com/blog/hacking-facebook-csrf-device-login-flow
https://stephensclafani.com/2014/07/29/hacking-facebooks-legacy-api-part-2-stealing-user-sessions/
https://isciurus.blogspot.ru/2013/04/a-story-of-9500-bug-in-facebook-oauth-20.html 
https://isciurus.blogspot.ca/2012/09/pwning-facebook-authorization-through.html 
http://homakov.blogspot.ca/2013/02/hacking-facebook-with-oauth2-and-chrome.html
https://blog.bentkowski.info/2014/09/in-this-post-ill-explain-to-you.html
https://prakharprasad.com/facebook-mailchimp-application-oauth-2-0-misconfiguration/
https://medu554.blogspot.com/2013/08/facebooks-parse-oauth-bug.html
http://breaksec.com/?p=5753
http://nirgoldshlager.blogspot.com/2013/02/how-i-hacked-facebook-oauth-to-get-full.html
http://blog.intothesymmetry.com/2014/04/oauth-2-how-i-have-hacked-facebook.html
https://whitton.io/articles/stealing-facebook-access-tokens-with-a-double-submit/
http://prosecco.gforge.inria.fr/CVE/Facebook_JS_2012.html
https://philippeharewood.com/swiping-facebook-official-access-tokens/
http://whitehatstories.blogspot.in/2017/05/oauth-token-validation-bug-in-facebook.html
https://medium.com/@lokeshdlk77/bypass-oauth-nonce-and-steal-oculus-response-code-faa9cc8d0d37
https://medium.com/@lokeshdlk77/stealing-facebook-mailchimp-application-oauth-2-0-access-token-3af51f89f5b0

#### Instagram<br>
One-click reflected XSS in www.instagram.com due to unfiltered URI schemes leads to account takeover
https://infosecwriteups.com/how-i-found-a-critical-bug-in-instagram-and-got-49500-bounty-from-facebook-626ff2c6a853
https://www.vulnano.com/2022/07/react-debugkeystore-key-was-trusted-by.html
https://medium.com/@the_null_kid/instagram-photo-was-present-in-data-backup-nearly-after-two-years-being-deleted-f0e4d6e108
https://medium.com/@avinash_/email-confirmation-bypass-at-instagram-cc968f9a126
http://www.iltalehti.fi/digi/2016050221506011_du.shtml
https://www.facebook.com/notes/kinghackx/breaking-video-calling-feature-in-instagram-app/522128951955609/
https://viaforensics.com/mobile-security/hacked-your-instagram-account.html 
https://josipfranjkovic.blogspot.com/2013/07/how-i-found-my-way-into-instagrams.html
http://breaksec.com/?p=6164
https://web.archive.org/web/20170702100704/http://insertco.in/2014/02/10/how-i-hacked-instagram/
https://whitton.io/articles/instagrams-one-click-privacy-switch/
https://samanfatahpour.blogspot.com/2014/10/facebook-bugbounty-facebook-instagram.html
https://www.arneswinnen.net/2016/02/the-tales-of-a-bug-bounty-hunter-10-interesting-vulnerabilities-in-instagram/
https://www.arneswinnen.net/2016/03/how-i-could-compromise-4-locked-instagram-accounts/
https://mohankallepalli.blogspot.com/2016/04/instagram-unauthorized-comment-deletion.html
https://www.arneswinnen.net/2016/05/instabrute-two-ways-to-brute-force-instagram-account-credentials/
http://bugdisclose.blogspot.in/2017/04/instagram-email-verification-issue.html
https://philippeharewood.com/find-instagram-contacts-for-any-user-on-facebook/
https://stefanovettorazzi.com/taking_over_instagram_accounts/
https://bugreader.com/majd@privilege-escalation-in-instagram-chat-groups-102?fbclid=IwAR0V9mh-9pT3oQ97eBvlNtY4LpvPw42mowDXkTtPTRcuNBYgoQpMmZoNSaQ

#### Signal<br>
https://philippeharewood.com/getting-facebook-signal-app-access-token/

#### Slingshot<br>
https://philippeharewood.com/add-any-facebook-user-non-friend-to-slingshot-without-knowing-the-username/

#### Messenger  Android<br>
https://servicenger.com/mobile/facebook-messenger-for-android-indirect-thread-deletion
https://www.aryansinha.com/2017/11/session-misconfiguration-in-messenger.html
https://www.vulnano.com/2019/03/facebook-messenger-server-random-memory.html

#### Moments<br>
https://philippeharewood.com/rewriting-a-photo-not-owned-by-the-session-user-in-moments-app/
https://philippeharewood.com/delete-any-moments-app-photo-or-folder-not-owned-by-the-session-user/

#### Moves<br>
https://web.archive.org/web/20171112164937/http://www.paulosyibelo.com:80/2015/12/facebooks-moves-oauth-xss.html

#### Whatsapp<br>
https://infosecwriteups.com/whatsapp-bug-bounty-bypassing-biometric-authentication-using-voip-87548ef7a0ba<br>
https://immukul.blogspot.in/2016/11/whatsapp-hacked.html
http://blog.pentestnepal.tech/post/156707088037/i-got-emails-g-suite-vulnerability
https://medium.com/bugbountywriteup/whatsapp-dos-vulnerability-in-ios-android-d896f76d3253
https://medium.com/bugbountywriteup/facebook-bug-bounty-reading-whatsapp-contacts-list-without-unlocking-the-device-a40e9c660a42

#### Workplace<br>
https://philippeharewood.com/a-walk-in-the-workplace/
https://www.youtube.com/watch?v=H0aQPcuskMo
https://medium.com/bugbountywriteup/facebook-workplace-privilege-escalation-vulnerability-to-change-the-post-privacy-as-public-634f1c995780

### Whitehat Test Accounts<br>
https://medium.com/@rohitcoder/whitehat-test-accounts-can-act-as-hidden-admin-with-business-manager-ad-accounts-ce75ead5ffff
[Ability to find Facebook employee’s test accounts which lead to the disclosure of internal information](https://ysamm.com/?p=638)<br>


### Facebook Event<br>
https://infosecwriteups.com/irremovable-guest-in-facebook-event-facebook-bug-bounty-e10e03c98cd5

### Facebook Business Page<br>
https://infosecwriteups.com/hacking-facebook-invoice-how-i-couldve-bought-anything-for-free-from-facebook-business-pages-42bcfaa73ec4

### DOS Attack<br>
https://www.yesnaveen.com/2022/05/remotely-permanent-crash-any-instagram.html?m=1

### Facebook/Instagram Mobile App <br>
[Taking over the Call to Action button on Mobile Devices](https://www.ash-king.co.uk/blog/abusing-Facebooks-call-to-action-to-launch-internal-deeplinks)<br>
[Facebook android webview vulnerability : Execute arbitrary javascript (xss) and load arbitrary website ](https://servicenger.com/mobile/facebook-android-webview-vulnerability/)<br>
[Instagram vulnerability : Turn off all type of message requests using deeplink (Android)](https://servicenger.com/mobile/instagram-vulnerability-turn-off-message-requests-deeplink/)<br>
[Facebook Messenger for android indirect thread deletion vulnerability.](https://servicenger.com/mobile/facebook-messenger-for-android-indirect-thread-deletion/)<br>
[Multiple bugs allowed malicious Android Applications to takeover Facebook/Workplace accounts](https://ysamm.com/?p=729)<br>
https://otmastimi.medium.com/users-location-diclosure-in-the-nearby-friends-feature-fabd24be05cb<br>
https://infosecwriteups.com/how-i-could-have-accessed-all-your-private-videos-photos-saved-inside-your-device-without-even-1a7e455ddcc8

