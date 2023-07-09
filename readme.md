# OpenAI for Adobe InDesign

Experimental UXP dialog to connect OpenAI with Adobe InDesign.

<img width="1920" alt="openAI_for_indesign" src="https://github.com/RolandDreger/indesign-openai/assets/19747449/c63b665c-a053-4ba5-b116-24a54ec5222b">

## Usage

1. Go to `Code` → `Download ZIP`
2. Create an account at [OpenAi](https://openai.com/) (if you don't already have one).
3. Create an API key under `User` → `API keys` and the button `Create new secret key`. 
4. Insert this key into the script code. Line 23: `var OPENAI_API_KEY = "YOUR_API_KEY";` 
5. Start the script `openai-4-indesign.idjs` with a double-click from the InDesign Script palette.

## Notes
### Text
Text selected in the InDesign document is inserted into the `Optional Content` field when the script starts. This is intended for larger amounts of text to be handled, e.g. translations.

Via `Insert` button the text in the current document selection will be replaced by the text in the `Result` field.

### Image
**Please note:** After inserting a generated image into the InDesign document by the script (via `Insert` button), it is initially stored only in the temporary folder on the computer. **If you want to keep the image, go to `Copy link to ...`** in the context menu of the Link palette. If not, the image file will be lost after shutdown. 

## Use Cases
Here are some use cases: [Translation, Text Shortening, Headline Creation](https://vimeo.com/836122207), [Images](https://vimeo.com/835233091?share=copy), [Index](https://vimeo.com/834805501)

You have others, please let me know ...

## Remark
I think many things about *»Artificial Intelligence«* are currently rightly criticized, such as high energy consumption, unclear copyright, discrimination by algorithms, dubious origin of the training data and also poor working conditions and payment of those who classified them. 

Nevertheless, AI has come to stay and offers many interesting new possibilities. Ultimately, everyone has to decide for themselves whether to use it or not. 

# Support
If you want to support the development of the script: 

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=roland%2edreger%40a1%2enet&lc=AT&item_name=Roland%20Dreger%20%2f%20Donation%20for%20script%20development%20openai-4-indesign&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

# License

[MIT](http://www.opensource.org/licenses/mit-license.php)


