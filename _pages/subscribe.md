---
layout: no-title
title: "Subscribe"
permalink: /subscribe/
---
<head>
<style>
    .grid-container {
        display: grid;
        grid-template-columns: 1fr 1fr; /* Two equal-width columns */
        gap: 20px; /* Space between columns */
    }
    @media (max-width: 600px) {
        .grid-container {
            max-width: 100%;
            grid-template-columns: 1fr;
        }
    }
</style>
</head>

{% capture mail_md %}
### Get Notified On Upcoming Events:
* General Meetings
* Reading Group, Workshops, etc.
* Chapter Socials, Hikes, Craft Nights, Movie Watchparties
* Action: Labor Solidarity, GOTV Campaigns, Mutual Aid and More!

---
{% endcapture %}

{% capture newsletter_md %}
### Emailed to you monthly, includes:
* Updates on Working Groups and Priority Campaigns
* Our Take on Local and National News
* Summary of Key Upcoming Events
* PDSA Statements, Endorsements and More!

---
{% endcapture %}

<div class = "grid-container">
    <div class = "column" id="mc_embed_shell">
        <h2>Mailing List</h2>
        <div>{{ mail_md | markdownify }}</div>
        <link href="//cdn-images.mailchimp.com/embedcode/classic-061523.css" rel="stylesheet" type="text/css">
        <style type="text/css">
                #mc_embed_signup{background:#fff; false;clear:left; font:14px Helvetica,Arial,sans-serif; width: 100%; max-width: 600px;}
                /* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
                We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
        </style>
        <div id="mc_embed_signup">
            <form action="https://twitter.us15.list-manage.com/subscribe/post?u=081245b4dc5f18f3a07fa71e2&amp;id=f1a89f28ee&amp;f_id=000f8ce0f0" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank">
                <div id="mc_embed_signup_scroll">
                    <div class="indicates-required"><span class="asterisk">*</span>indicates required</div>
                    <div class="mc-field-group"><label for="mce-EMAIL">Email Address <span class="asterisk">*</span></label><input type="email" name="EMAIL" class="required email" id="mce-EMAIL" required="" value=""></div>
                    <div class="mc-field-group"><label for="mce-FNAME">First Name <span class="asterisk">*</span></label><input type="text" name="FNAME" class="required text" id="mce-FNAME" value="" required=""></div>
                    <div class="mc-field-group"><label for="mce-LNAME">Last Name </label><input type="text" name="LNAME" class=" text" id="mce-LNAME" value=""></div>
                    <div class="mc-field-group"><label for="mce-CITY">City <span class="asterisk">*</span></label><input type="text" name="CITY" class="required text" id="mce-CITY" value="" required=""></div>
                    <div class="mc-field-group input-group"><strong>DSA Member </strong><ul><li><input type="radio" name="MMERGE7" id="mce-MMERGE70" value="Yes"><label for="mce-MMERGE70">Yes</label></li><li><input type="radio" name="MMERGE7" id="mce-MMERGE71" value="No"><label for="mce-MMERGE71">No</label></li></ul></div>
                    <div class="mc-field-group input-group"><strong>Union Member <span class="asterisk">*</span></strong><ul><li><input type="radio" name="MMERGE11" id="mce-MMERGE110" value="Yes"><label for="mce-MMERGE110">Yes</label></li><li><input type="radio" name="MMERGE11" id="mce-MMERGE111" value="No"><label for="mce-MMERGE111">No</label></li></ul></div>
                    <div id="mce-responses" class="clear foot">
                        <div class="response" id="mce-error-response" style="display: none;"></div>
                        <div class="response" id="mce-success-response" style="display: none;"></div>
                    </div>
                    <div aria-hidden="true" style="position: absolute; left: -5000px;">
                        /* real people should not fill this in and expect good things - do not remove this or risk form bot signups */
                        <input type="text" name="b_081245b4dc5f18f3a07fa71e2_f1a89f28ee" tabindex="-1" value="">
                    </div>
                    <div class="optionalParent">
                        <div class="clear foot">
                            <input type="submit" name="subscribe" id="mc-embedded-subscribe" class="button" value="Subscribe">
                            <p style="margin: 0px auto;"><a href="http://eepurl.com/hqV_vHNP0K" title="Mailchimp - email marketing made easy and fun"><span style="display: inline-block; background-color: transparent; border-radius: 4px;"><img class="refferal_badge" src="https://digitalasset.intuit.com/render/content/dam/intuit/mc-fe/en_us/images/intuit-mc-rewards-text-dark.svg" alt="Intuit Mailchimp" style="width: 220px; height: 40px; display: flex; padding: 2px 0px; justify-content: center; align-items: center;"></span></a></p>
                        </div>
                    </div>
                </div>
            </form>
        </div>
        <div>
        </div>
    </div>
    <div class = "column">
      <h2>Chapter Newsletter</h2>
      <div>{{ newsletter_md | markdownify }}</div>
      <iframe src="https://peninsuladsa.substack.com/embed" style="width: 100%; aspect-ratio: 3 / 2; border: 1px solid #EEE; background: white; overflow: hidden;" frameborder="0" scrolling="no">
      </iframe>
      <div>
      </div>
    </div>
</div>






<script type="text/javascript" src="//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js"></script><script type="text/javascript" src="//s3.amazonaws.com/downloads.mailchimp.com/js/mc-sms-phone.js"></script><script type="text/javascript">(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[2]='LNAME';ftypes[2]='text';fnames[4]='CITY';ftypes[4]='text';fnames[7]='MMERGE7';ftypes[7]='radio';fnames[11]='MMERGE11';ftypes[11]='radio';fnames[3]='MMERGE3';ftypes[3]='text';fnames[5]='ZIPCODE';ftypes[5]='text';fnames[6]='MMERGE6';ftypes[6]='text';fnames[8]='MMERGE8';ftypes[8]='radio';fnames[10]='MMERGE10';ftypes[10]='date';fnames[9]='MMERGE9';ftypes[9]='date';fnames[12]='MMERGE12';ftypes[12]='number';}(jQuery));var $mcj = jQuery.noConflict(true);
    // SMS Phone Multi-Country Functionality
    if(!window.MC) {
      window.MC = {};
    }
    window.MC.smsPhoneData = {
      defaultCountryCode: 'US',
      programs: [],
      smsProgramDataCountryNames: []
    };

    function getCountryUnicodeFlag(countryCode) {
       return countryCode.toUpperCase().replace(/./g, (char) => String.fromCodePoint(char.charCodeAt(0) + 127397))
    };

    // HTML sanitization function to prevent XSS
    function sanitizeHtml(str) {
      if (typeof str !== 'string') return '';
      return str
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;')
        .replace(/'/g, '&#x27;')
        .replace(/\//g, '&#x2F;');
    }

    // URL sanitization function to prevent javascript: and data: URLs
    function sanitizeUrl(url) {
      if (typeof url !== 'string') return '';
      const trimmedUrl = url.trim().toLowerCase();
      if (trimmedUrl.startsWith('javascript:') || trimmedUrl.startsWith('data:') || trimmedUrl.startsWith('vbscript:')) {
        return '#';
      }
      return url;
    }

    const getBrowserLanguage = () => {
      if (!window?.navigator?.language?.split('-')[1]) {
        return window?.navigator?.language?.toUpperCase();
      }
      return window?.navigator?.language?.split('-')[1];
    };

    
    // getBrowserLanguageCode() and getSmsProgramForCountryAndLanguage() are provided globally
    // by the external mc-sms-phone.js script loaded alongside this inline form script.

    function getDefaultCountryProgram(defaultCountryCode, smsProgramData) {
      if (!smsProgramData || smsProgramData.length === 0) {
        return null;
      }
      var browserCountryCode = getBrowserLanguage();
      var browserLangCode = getBrowserLanguageCode();
      if (browserCountryCode) {
        var match = getSmsProgramForCountryAndLanguage(smsProgramData, browserCountryCode, browserLangCode);
        if (match) { return match; }
      }
      if (defaultCountryCode) {
        var match = getSmsProgramForCountryAndLanguage(smsProgramData, defaultCountryCode, browserLangCode);
        if (match) { return match; }
      }
      return smsProgramData[0];
    }

    function updateSmsLegalText(countryCode, fieldName) {
      if (!countryCode || !fieldName) {
        return;
      }
      var programs = window?.MC?.smsPhoneData?.programs;
      if (!programs || !Array.isArray(programs)) {
        return;
      }
      var browserLangCode = getBrowserLanguageCode();
      var program = getSmsProgramForCountryAndLanguage(programs, countryCode, browserLangCode);
      if (!program || !program.requiredTemplate) {
        return;
      }
    
      
      var smsConsentHtmlRenderingFixEnabled = true;
      
      const legalTextElement = document.querySelector('#legal-text-' + fieldName);
      if (!legalTextElement) {
        return;
      }
      
      const divRegex = new RegExp('</?[div][^>]*>', 'gi');
      const blockWrapperRegex = new RegExp('</?(?:div|p)[^>]*>', 'gi');
      const fullAnchorRegex = new RegExp('<a.*?</a>', 'g');
      const anchorRegex = new RegExp('<a href="(.*?)" target="(.*?)">(.*?)</a>');
      
      const template = smsConsentHtmlRenderingFixEnabled
        ? program.requiredTemplate
            .replace(/<\/p>\s*<p[^>]*>/gi, ' ')
            .replace(blockWrapperRegex, '')
        : program.requiredTemplate.replace(divRegex, '');
      
      

      legalTextElement.textContent = '';
      const parts = template.split(/(<a href=".*?"(?: target=".*?")?>.*?<\/a>)/g);
      parts.forEach(function(part) {
        if (!part) {
          return;
        }
        const anchorMatch = part.match(/<a href="(.*?)"(?: target="(.*?)")?>(.+?)<\/a>/);
        if (anchorMatch) {
          const linkElement = document.createElement('a');
          linkElement.href = sanitizeUrl(anchorMatch[1]);
          linkElement.target = anchorMatch[2] ? sanitizeHtml(anchorMatch[2]) : '_blank';
          linkElement.rel = 'noopener noreferrer';
          linkElement.textContent = sanitizeHtml(anchorMatch[3]);
          legalTextElement.appendChild(linkElement);
        } else {
          legalTextElement.appendChild(document.createTextNode(part));
        }
      });
          
    }

    function generateDropdownOptions(smsProgramData) {
      if (!smsProgramData || smsProgramData.length === 0) {
        return '';
      }

      var programs = true
        ? smsProgramData.filter(function(p, i, arr) {
            return arr.findIndex(function(q) { return q.countryCode === p.countryCode; }) === i;
          })
        : smsProgramData;
      
      return programs.map(program => {
        const flag = getCountryUnicodeFlag(program.countryCode);
        const countryName = getCountryName(program.countryCode);
        const callingCode = program.countryCallingCode || '';
        // Sanitize all values to prevent XSS
        const sanitizedCountryCode = sanitizeHtml(program.countryCode || '');
        const sanitizedCountryName = sanitizeHtml(countryName || '');
        const sanitizedCallingCode = sanitizeHtml(callingCode || '');
        return '<option value="' + sanitizedCountryCode + '">' + sanitizedCountryName + ' ' + sanitizedCallingCode + '</option>';
      }).join('');
    }

    function getCountryName(countryCode) {
      if (window.MC?.smsPhoneData?.smsProgramDataCountryNames && Array.isArray(window.MC.smsPhoneData.smsProgramDataCountryNames)) {
        for (let i = 0; i < window.MC.smsPhoneData.smsProgramDataCountryNames.length; i++) {
          if (window.MC.smsPhoneData.smsProgramDataCountryNames[i].code === countryCode) {
            return window.MC.smsPhoneData.smsProgramDataCountryNames[i].name;
          }
        }
      }
      return countryCode;
    }

    function getDefaultPlaceholder(countryCode) {
      if (!countryCode || typeof countryCode !== 'string') {
        return '+1 000 000 0000'; // Default US placeholder
      }
      
            var mockPlaceholders = [
        {
          countryCode: 'US',
          placeholder: '+1 000 000 0000',
          helpText: 'Include the US country code +1 before the phone number',
        },
        {
          countryCode: 'GB',
          placeholder: '+44 0000 000000',
          helpText: 'Include the GB country code +44 before the phone number',
        },
        {
          countryCode: 'CA',
          placeholder: '+1 000 000 0000',
          helpText: 'Include the CA country code +1 before the phone number',
        },
        {
          countryCode: 'AU',
          placeholder: '+61 000 000 000',
          helpText: 'Include the AU country code +61 before the phone number',
        },
        {
          countryCode: 'DE',
          placeholder: '+49 000 0000000',
          helpText: 'Fügen Sie vor der Telefonnummer die DE-Ländervorwahl +49 ein',
        },
        {
          countryCode: 'FR',
          placeholder: '+33 0 00 00 00 00',
          helpText: 'Incluez le code pays FR +33 avant le numéro de téléphone',
        },
        {
          countryCode: 'ES',
          placeholder: '+34 000 000 000',
          helpText: 'Incluya el código de país ES +34 antes del número de teléfono',
        },
        {
          countryCode: 'NL',
          placeholder: '+31 0 00000000',
          helpText: 'Voeg de NL-landcode +31 toe vóór het telefoonnummer',
        },
        {
          countryCode: 'BE',
          placeholder: '+32 000 00 00 00',
          helpText: 'Incluez le code pays BE +32 avant le numéro de téléphone',
        },
        {
          countryCode: 'CH',
          placeholder: '+41 00 000 00 00',
          helpText: 'Fügen Sie vor der Telefonnummer die CH-Ländervorwahl +41 ein',
        },
        {
          countryCode: 'AT',
          placeholder: '+43 000 000 0000',
          helpText: 'Fügen Sie vor der Telefonnummer die AT-Ländervorwahl +43 ein',
        },
        {
          countryCode: 'IE',
          placeholder: '+353 00 000 0000',
          helpText: 'Include the IE country code +353 before the phone number',
        },
        {
          countryCode: 'IT',
          placeholder: '+39 000 000 0000',
          helpText: 'Includere il prefisso internazionale IT +39 prima del numero di telefono',
        },
        {
          countryCode: 'NO',
          placeholder: '+47 000 00 000',
          helpText: 'Inkluder NO landskode +47 før telefonnummeret',
        },
        {
          countryCode: 'SE',
          placeholder: '+46 00 000 00 00',
          helpText: 'Inkludera SE landskod +46 före telefonnumret',
        },
        {
          countryCode: 'DK',
          placeholder: '+45 00 00 00 00',
          helpText: 'Inkluder DK landekode +45 før telefonnummeret',
        },
        {
          countryCode: 'FI',
          placeholder: '+358 00 000 0000',
          helpText: 'Sisällytä FI-maakoodi +358 ennen puhelinnumeroa',
        },
        {
          countryCode: 'EE',
          placeholder: '+372 0000 0000',
          helpText: 'Lisage EE riigikood +372 telefoninumbri ette',
        },
        {
          countryCode: 'PL',
          placeholder: '+48 000 000 000',
          helpText: 'Podaj numer kierunkowy PL +48 przed numerem telefonu',
        },
        {
          countryCode: 'SK',
          placeholder: '+421 000 000 000',
          helpText: 'Pred telefónne číslo uveďte kód krajiny SK +421',
        },
        {
          countryCode: 'LV',
          placeholder: '+371 0000 0000',
          helpText: 'Iekļaujiet LV valsts kodu +371 pirms tālruņa numura',
        },
        {
          countryCode: 'LT',
          placeholder: '+370 0000 0000',
          helpText: 'Įtraukite LT šalies kodą +370 prieš telefono numerį',
        },
        {
          countryCode: 'GR',
          placeholder: '+30 000 000 0000',
          helpText: 'Συμπεριλάβετε τον κωδικό χώρας GR +30 πριν από τον αριθμό τηλεφώνου',
        },
        {
          countryCode: 'PT',
          placeholder: '+351 000 000 000',
          helpText: 'Inclua o código de país PT +351 antes do número de telefone',
        },
        {
          countryCode: 'HR',
          placeholder: '+385 00 000 0000',
          helpText: 'Uključite HR pozivni broj države +385 prije telefonskog broja',
        },
        {
          countryCode: 'SI',
          placeholder: '+386 00 000 000',
          helpText: 'Vključite SI kodo države +386 pred telefonsko številko',
        },
        {
          countryCode: 'IS',
          placeholder: '+354 000 0000',
          helpText: 'Láttu IS landsnúmer +354 fylgja á undan símanúmerinu',
        },
        {
          countryCode: 'LU',
          placeholder: '+352 000 000 000',
          helpText: 'Incluez le code pays LU +352 avant le numéro de téléphone',
        },
        {
          countryCode: 'MC',
          placeholder: '+377 00 00 00 00',
          helpText: 'Incluez le code pays MC +377 avant le numéro de téléphone',
        },
        {
          countryCode: 'AD',
          placeholder: '+376 000 000',
          helpText: 'Incloeu el codi de país AD +376 abans del número de telèfon',
        },
        {
          countryCode: 'JE',
          placeholder: '+44 0000 000000',
          helpText: 'Include the JE country code +44 before the phone number',
        },
        {
          countryCode: 'IM',
          placeholder: '+44 0000 000000',
          helpText: 'Include the IM country code +44 before the phone number',
        },
        {
          countryCode: 'GG',
          placeholder: '+44 0000 000000',
          helpText: 'Include the GG country code +44 before the phone number',
        },
        {
          countryCode: 'AL',
          placeholder: '+355 00 000 0000',
          helpText: 'Përfshini kodin e vendit AL +355 para numrit të telefonit',
        },
        {
          countryCode: 'SM',
          placeholder: '+378 0000 000000',
          helpText: 'Includere il prefisso internazionale SM +378 prima del numero di telefono',
        },
        {
          countryCode: 'FO',
          placeholder: '+298 000000',
          helpText: 'Inkluder FO landekode +298 før telefonnummeret',
        },
        {
          countryCode: 'MT',
          placeholder: '+356 0000 0000',
          helpText: 'Include the MT country code +356 before the phone number',
        },
        {
          countryCode: 'LI',
          placeholder: '+423 000 0000',
          helpText: 'Fügen Sie vor der Telefonnummer die LI-Ländervorwahl +423 ein',
        },
        {
          countryCode: 'GI',
          placeholder: '+350 000 00000',
          helpText: 'Include the GI country code +350 before the phone number',
        },
        {
          countryCode: 'MD',
          placeholder: '+373 00 000 000',
          helpText: 'Includeți codul de țară MD +373 înaintea numărului de telefon',
        },
        {
          countryCode: 'HU',
          placeholder: '+36 00 000 0000',
          helpText: 'A telefonszám előtt adja meg a HU országkódot +36',
        },
        {
          countryCode: 'NZ',
          placeholder: '+64 00 000 0000',
          helpText: 'Include the NZ country code +64 before the phone number',
        },
        {
          countryCode: 'ME',
          placeholder: '+382 00 000 000',
          helpText: 'Uključite ME pozivni broj države +382 prije telefonskog broja',
        },
      ];

      const selectedPlaceholder = mockPlaceholders.find(function(item) {
        return item && item.countryCode === countryCode;
      });
      
      return selectedPlaceholder ? selectedPlaceholder.placeholder : mockPlaceholders[0].placeholder;
    }

    function updatePlaceholder(countryCode, fieldName) {
      if (!countryCode || !fieldName) {
        return;
      }
      
      const phoneInput = document.querySelector('#mce-' + fieldName);
      if (!phoneInput) {
        return;
      }
      
      const placeholder = getDefaultPlaceholder(countryCode);
      if (placeholder) {
        phoneInput.placeholder = placeholder;
      }
    }

    function updateCountryCodeInstruction(countryCode, fieldName) {
      updatePlaceholder(countryCode, fieldName);
      
    }

    function getDefaultHelpText(countryCode) {
      var mockPlaceholders = [
        {
          countryCode: 'US',
          placeholder: '+1 000 000 0000',
          helpText: 'Include the US country code +1 before the phone number',
        },
        {
          countryCode: 'GB',
          placeholder: '+44 0000 000000',
          helpText: 'Include the GB country code +44 before the phone number',
        },
        {
          countryCode: 'CA',
          placeholder: '+1 000 000 0000',
          helpText: 'Include the CA country code +1 before the phone number',
        },
        {
          countryCode: 'AU',
          placeholder: '+61 000 000 000',
          helpText: 'Include the AU country code +61 before the phone number',
        },
        {
          countryCode: 'DE',
          placeholder: '+49 000 0000000',
          helpText: 'Fügen Sie vor der Telefonnummer die DE-Ländervorwahl +49 ein',
        },
        {
          countryCode: 'FR',
          placeholder: '+33 0 00 00 00 00',
          helpText: 'Incluez le code pays FR +33 avant le numéro de téléphone',
        },
        {
          countryCode: 'ES',
          placeholder: '+34 000 000 000',
          helpText: 'Incluya el código de país ES +34 antes del número de teléfono',
        },
        {
          countryCode: 'NL',
          placeholder: '+31 0 00000000',
          helpText: 'Voeg de NL-landcode +31 toe vóór het telefoonnummer',
        },
        {
          countryCode: 'BE',
          placeholder: '+32 000 00 00 00',
          helpText: 'Incluez le code pays BE +32 avant le numéro de téléphone',
        },
        {
          countryCode: 'CH',
          placeholder: '+41 00 000 00 00',
          helpText: 'Fügen Sie vor der Telefonnummer die CH-Ländervorwahl +41 ein',
        },
        {
          countryCode: 'AT',
          placeholder: '+43 000 000 0000',
          helpText: 'Fügen Sie vor der Telefonnummer die AT-Ländervorwahl +43 ein',
        },
        {
          countryCode: 'IE',
          placeholder: '+353 00 000 0000',
          helpText: 'Include the IE country code +353 before the phone number',
        },
        {
          countryCode: 'IT',
          placeholder: '+39 000 000 0000',
          helpText: 'Includere il prefisso internazionale IT +39 prima del numero di telefono',
        },
        {
          countryCode: 'NO',
          placeholder: '+47 000 00 000',
          helpText: 'Inkluder NO landskode +47 før telefonnummeret',
        },
        {
          countryCode: 'SE',
          placeholder: '+46 00 000 00 00',
          helpText: 'Inkludera SE landskod +46 före telefonnumret',
        },
        {
          countryCode: 'DK',
          placeholder: '+45 00 00 00 00',
          helpText: 'Inkluder DK landekode +45 før telefonnummeret',
        },
        {
          countryCode: 'FI',
          placeholder: '+358 00 000 0000',
          helpText: 'Sisällytä FI-maakoodi +358 ennen puhelinnumeroa',
        },
        {
          countryCode: 'EE',
          placeholder: '+372 0000 0000',
          helpText: 'Lisage EE riigikood +372 telefoninumbri ette',
        },
        {
          countryCode: 'PL',
          placeholder: '+48 000 000 000',
          helpText: 'Podaj numer kierunkowy PL +48 przed numerem telefonu',
        },
        {
          countryCode: 'SK',
          placeholder: '+421 000 000 000',
          helpText: 'Pred telefónne číslo uveďte kód krajiny SK +421',
        },
        {
          countryCode: 'LV',
          placeholder: '+371 0000 0000',
          helpText: 'Iekļaujiet LV valsts kodu +371 pirms tālruņa numura',
        },
        {
          countryCode: 'LT',
          placeholder: '+370 0000 0000',
          helpText: 'Įtraukite LT šalies kodą +370 prieš telefono numerį',
        },
        {
          countryCode: 'GR',
          placeholder: '+30 000 000 0000',
          helpText: 'Συμπεριλάβετε τον κωδικό χώρας GR +30 πριν από τον αριθμό τηλεφώνου',
        },
        {
          countryCode: 'PT',
          placeholder: '+351 000 000 000',
          helpText: 'Inclua o código de país PT +351 antes do número de telefone',
        },
        {
          countryCode: 'HR',
          placeholder: '+385 00 000 0000',
          helpText: 'Uključite HR pozivni broj države +385 prije telefonskog broja',
        },
        {
          countryCode: 'SI',
          placeholder: '+386 00 000 000',
          helpText: 'Vključite SI kodo države +386 pred telefonsko številko',
        },
        {
          countryCode: 'IS',
          placeholder: '+354 000 0000',
          helpText: 'Láttu IS landsnúmer +354 fylgja á undan símanúmerinu',
        },
        {
          countryCode: 'LU',
          placeholder: '+352 000 000 000',
          helpText: 'Incluez le code pays LU +352 avant le numéro de téléphone',
        },
        {
          countryCode: 'MC',
          placeholder: '+377 00 00 00 00',
          helpText: 'Incluez le code pays MC +377 avant le numéro de téléphone',
        },
        {
          countryCode: 'AD',
          placeholder: '+376 000 000',
          helpText: 'Incloeu el codi de país AD +376 abans del número de telèfon',
        },
        {
          countryCode: 'JE',
          placeholder: '+44 0000 000000',
          helpText: 'Include the JE country code +44 before the phone number',
        },
        {
          countryCode: 'IM',
          placeholder: '+44 0000 000000',
          helpText: 'Include the IM country code +44 before the phone number',
        },
        {
          countryCode: 'GG',
          placeholder: '+44 0000 000000',
          helpText: 'Include the GG country code +44 before the phone number',
        },
        {
          countryCode: 'AL',
          placeholder: '+355 00 000 0000',
          helpText: 'Përfshini kodin e vendit AL +355 para numrit të telefonit',
        },
        {
          countryCode: 'SM',
          placeholder: '+378 0000 000000',
          helpText: 'Includere il prefisso internazionale SM +378 prima del numero di telefono',
        },
        {
          countryCode: 'FO',
          placeholder: '+298 000000',
          helpText: 'Inkluder FO landekode +298 før telefonnummeret',
        },
        {
          countryCode: 'MT',
          placeholder: '+356 0000 0000',
          helpText: 'Include the MT country code +356 before the phone number',
        },
        {
          countryCode: 'LI',
          placeholder: '+423 000 0000',
          helpText: 'Fügen Sie vor der Telefonnummer die LI-Ländervorwahl +423 ein',
        },
        {
          countryCode: 'GI',
          placeholder: '+350 000 00000',
          helpText: 'Include the GI country code +350 before the phone number',
        },
        {
          countryCode: 'MD',
          placeholder: '+373 00 000 000',
          helpText: 'Includeți codul de țară MD +373 înaintea numărului de telefon',
        },
        {
          countryCode: 'HU',
          placeholder: '+36 00 000 0000',
          helpText: 'A telefonszám előtt adja meg a HU országkódot +36',
        },
        {
          countryCode: 'NZ',
          placeholder: '+64 00 000 0000',
          helpText: 'Include the NZ country code +64 before the phone number',
        },
        {
          countryCode: 'ME',
          placeholder: '+382 00 000 000',
          helpText: 'Uključite ME pozivni broj države +382 prije telefonskog broja',
        },
      ];
      
      if (!countryCode || typeof countryCode !== 'string') {
        return mockPlaceholders[0].helpText;
      }
      
      const selectedHelpText = mockPlaceholders.find(function(item) {
          return item && item.countryCode === countryCode;
        });
        
        return selectedHelpText ? selectedHelpText.helpText : mockPlaceholders[0].helpText;
    }

    function setDefaultHelpText(countryCode) {
      const helpTextSpan = document.querySelector('#help-text');
      if (!helpTextSpan) {
        return;
      }

        
    }

    function updateHelpTextCountryCode(countryCode, fieldName) {
      if (!countryCode || !fieldName) {
        return;
      }
      
      setDefaultHelpText(countryCode);
    }

    function initializeSmsPhoneDropdown(fieldName) {
      if (!fieldName || typeof fieldName !== 'string') {
        return;
      }
      
      const dropdown = document.querySelector('#country-select-' + fieldName);
      const displayFlag = document.querySelector('#flag-display-' + fieldName);
      
      if (!dropdown || !displayFlag) {
        return;
      }

      const smsPhoneData = window.MC?.smsPhoneData;
      if (smsPhoneData && smsPhoneData.programs && Array.isArray(smsPhoneData.programs)) {
        dropdown.innerHTML = generateDropdownOptions(smsPhoneData.programs);
      }

      const defaultProgram = getDefaultCountryProgram(smsPhoneData?.defaultCountryCode, smsPhoneData?.programs);
      if (defaultProgram && defaultProgram.countryCode) {
        dropdown.value = defaultProgram.countryCode;
        
        const flagSpan = displayFlag?.querySelector('#flag-emoji-' + fieldName);
        if (flagSpan) {
          flagSpan.textContent = getCountryUnicodeFlag(defaultProgram.countryCode);
          flagSpan.setAttribute('aria-label', sanitizeHtml(defaultProgram.countryCode) + ' flag');
        }
        
        updateSmsLegalText(defaultProgram.countryCode, fieldName);
        updatePlaceholder(defaultProgram.countryCode, fieldName);
        updateCountryCodeInstruction(defaultProgram.countryCode, fieldName);
      }

     
      var smsNotRequiredRemoveCountryCodeEnabled = true;
      var smsField = Object.values({"EMAIL":{"name":"EMAIL","label":"Email Address","helper_text":"","type":"email","required":true,"audience_field_name":"Email Address","merge_id":0,"help_text_enabled":false,"enabled":true,"order":0,"field_type":"merge"},"FNAME":{"name":"FNAME","label":"First Name","helper_text":"","type":"text","required":true,"audience_field_name":"First Name","merge_id":1,"help_text_enabled":false,"enabled":true,"order":1,"field_type":"merge"},"LNAME":{"name":"LNAME","label":"Last Name","helper_text":"","type":"text","required":false,"audience_field_name":"Last Name","merge_id":2,"help_text_enabled":false,"enabled":true,"order":2,"field_type":"merge"},"CITY":{"name":"CITY","label":"City","helper_text":"","type":"text","required":true,"audience_field_name":"City","merge_id":4,"help_text_enabled":false,"enabled":true,"order":3,"field_type":"merge"},"MMERGE7":{"name":"MMERGE7","label":"DSA Member","helper_text":"","type":"radio","required":false,"audience_field_name":"DSA Member","choices":[{"value":"Yes","label":"Yes"},{"value":"No","label":"No"}],"merge_id":7,"help_text_enabled":false,"enabled":true,"order":4,"field_type":"merge"},"MMERGE11":{"name":"MMERGE11","label":"Union Member","helper_text":"","type":"radio","required":true,"audience_field_name":"Union Member","choices":[{"value":"Yes","label":"Yes"},{"value":"No","label":"No"}],"merge_id":11,"help_text_enabled":false,"enabled":true,"order":5,"field_type":"merge"},"MMERGE3":{"name":"MMERGE3","label":"Phone Number","helper_text":"","type":"text","required":false,"audience_field_name":"Phone Number","enabled":false,"order":null,"field_type":"merge","merge_id":3},"ZIPCODE":{"name":"ZIPCODE","label":"Zip Code","helper_text":"","type":"text","required":false,"audience_field_name":"Zip Code","enabled":false,"order":null,"field_type":"merge","merge_id":5},"MMERGE6":{"name":"MMERGE6","label":"Notes","helper_text":"","type":"text","required":false,"audience_field_name":"Notes","enabled":false,"order":null,"field_type":"merge","merge_id":6},"MMERGE8":{"name":"MMERGE8","label":"Membership Type","helper_text":"","type":"radio","required":false,"audience_field_name":"Membership Type","choices":[{"value":"Monthly","label":"Monthly"},{"value":"Annual","label":"Annual"},{"value":"Non-dues paying","label":"Non-dues paying"},{"value":"Lifetime","label":"Lifetime"},{"value":"N/A","label":"N/A"}],"enabled":false,"order":null,"field_type":"merge","merge_id":8},"MMERGE10":{"name":"MMERGE10","label":"DSA Join Date","helper_text":"","type":"date","required":false,"audience_field_name":"DSA Join Date","dateformat":"MM/DD/YYYY","enabled":false,"order":null,"field_type":"merge","merge_id":10},"MMERGE9":{"name":"MMERGE9","label":"DSA Expire Date","helper_text":"","type":"date","required":false,"audience_field_name":"DSA Expire Date","dateformat":"MM/DD/YYYY","enabled":false,"order":null,"field_type":"merge","merge_id":9},"MMERGE12":{"name":"MMERGE12","label":"AK_ID","helper_text":"","type":"number","required":false,"audience_field_name":"AK_ID","enabled":false,"order":null,"field_type":"merge","merge_id":12}}).find(function(f) { return f.name === fieldName && f.type === 'smsphone'; });
      var isRequired = smsField ? smsField.required : false;
      var shouldAppendCountryCode = smsNotRequiredRemoveCountryCodeEnabled ? isRequired : true;
      
      var phoneInput = document.querySelector('#mce-' + fieldName);
      if (phoneInput && defaultProgram.countryCallingCode && shouldAppendCountryCode) {
        phoneInput.value = defaultProgram.countryCallingCode;
      }
      


      displayFlag?.addEventListener('click', function(e) {
        dropdown.focus();
      });


      dropdown?.addEventListener('change', function() {
        const selectedCountry = this.value;
        
        if (!selectedCountry || typeof selectedCountry !== 'string') {
          return;
        }
        
        const flagSpan = displayFlag?.querySelector('#flag-emoji-' + fieldName);
        if (flagSpan) {
          flagSpan.textContent = getCountryUnicodeFlag(selectedCountry);
          flagSpan.setAttribute('aria-label', sanitizeHtml(selectedCountry) + ' flag');
        }

         
        const selectedProgram = window.MC?.smsPhoneData?.programs.find(function(program) {
          return program && program.countryCode === selectedCountry;
        });

        var smsNotRequiredRemoveCountryCodeEnabled = true;
        var smsField = Object.values({"EMAIL":{"name":"EMAIL","label":"Email Address","helper_text":"","type":"email","required":true,"audience_field_name":"Email Address","merge_id":0,"help_text_enabled":false,"enabled":true,"order":0,"field_type":"merge"},"FNAME":{"name":"FNAME","label":"First Name","helper_text":"","type":"text","required":true,"audience_field_name":"First Name","merge_id":1,"help_text_enabled":false,"enabled":true,"order":1,"field_type":"merge"},"LNAME":{"name":"LNAME","label":"Last Name","helper_text":"","type":"text","required":false,"audience_field_name":"Last Name","merge_id":2,"help_text_enabled":false,"enabled":true,"order":2,"field_type":"merge"},"CITY":{"name":"CITY","label":"City","helper_text":"","type":"text","required":true,"audience_field_name":"City","merge_id":4,"help_text_enabled":false,"enabled":true,"order":3,"field_type":"merge"},"MMERGE7":{"name":"MMERGE7","label":"DSA Member","helper_text":"","type":"radio","required":false,"audience_field_name":"DSA Member","choices":[{"value":"Yes","label":"Yes"},{"value":"No","label":"No"}],"merge_id":7,"help_text_enabled":false,"enabled":true,"order":4,"field_type":"merge"},"MMERGE11":{"name":"MMERGE11","label":"Union Member","helper_text":"","type":"radio","required":true,"audience_field_name":"Union Member","choices":[{"value":"Yes","label":"Yes"},{"value":"No","label":"No"}],"merge_id":11,"help_text_enabled":false,"enabled":true,"order":5,"field_type":"merge"},"MMERGE3":{"name":"MMERGE3","label":"Phone Number","helper_text":"","type":"text","required":false,"audience_field_name":"Phone Number","enabled":false,"order":null,"field_type":"merge","merge_id":3},"ZIPCODE":{"name":"ZIPCODE","label":"Zip Code","helper_text":"","type":"text","required":false,"audience_field_name":"Zip Code","enabled":false,"order":null,"field_type":"merge","merge_id":5},"MMERGE6":{"name":"MMERGE6","label":"Notes","helper_text":"","type":"text","required":false,"audience_field_name":"Notes","enabled":false,"order":null,"field_type":"merge","merge_id":6},"MMERGE8":{"name":"MMERGE8","label":"Membership Type","helper_text":"","type":"radio","required":false,"audience_field_name":"Membership Type","choices":[{"value":"Monthly","label":"Monthly"},{"value":"Annual","label":"Annual"},{"value":"Non-dues paying","label":"Non-dues paying"},{"value":"Lifetime","label":"Lifetime"},{"value":"N/A","label":"N/A"}],"enabled":false,"order":null,"field_type":"merge","merge_id":8},"MMERGE10":{"name":"MMERGE10","label":"DSA Join Date","helper_text":"","type":"date","required":false,"audience_field_name":"DSA Join Date","dateformat":"MM/DD/YYYY","enabled":false,"order":null,"field_type":"merge","merge_id":10},"MMERGE9":{"name":"MMERGE9","label":"DSA Expire Date","helper_text":"","type":"date","required":false,"audience_field_name":"DSA Expire Date","dateformat":"MM/DD/YYYY","enabled":false,"order":null,"field_type":"merge","merge_id":9},"MMERGE12":{"name":"MMERGE12","label":"AK_ID","helper_text":"","type":"number","required":false,"audience_field_name":"AK_ID","enabled":false,"order":null,"field_type":"merge","merge_id":12}}).find(function(f) { return f.name === fieldName && f.type === 'smsphone'; });
        var isRequired = smsField ? smsField.required : false;
        var shouldAppendCountryCode = smsNotRequiredRemoveCountryCodeEnabled ? isRequired : true;
        
        var phoneInput = document.querySelector('#mce-' + fieldName);
        if (phoneInput && selectedProgram.countryCallingCode && shouldAppendCountryCode) {
          phoneInput.value = selectedProgram.countryCallingCode;
        }
        
        
        updateSmsLegalText(selectedCountry, fieldName);
        updatePlaceholder(selectedCountry, fieldName);
        updateCountryCodeInstruction(selectedCountry, fieldName);
      });
    }

    document.addEventListener('DOMContentLoaded', function() {
      const smsPhoneFields = document.querySelectorAll('[id^="country-select-"]');
      
      smsPhoneFields.forEach(function(dropdown) {
        const fieldName = dropdown?.id.replace('country-select-', '');
        initializeSmsPhoneDropdown(fieldName);
      });
    });
</script>