# Transskribi sonon venantan de krozila langeto per AI

Estas prezentata Tampermonkey-skripto, por transskribi per la OpenAI-API sonon venantan de krozila langeto.

## Instalado

1. Instalu **Tampermonkey** por via krozilo lau la instruoj che [tampermonkey.net](https://www.tampermonkey.net/).
2. Uzu au kreu [OpenAI-API-shlosilon](https://platform.openai.com/api-keys).
3. Malfermu [transskribi.js](./transskribi.js), alklaku **Raw** kaj kopiu la tutan kodon.
4. En la menuo de Tampermonkey elektu **krei novan skripton**. Forigu la ekzemplan kodon kaj algluu la kopiitan kodon.
5. Enmetu vian OpenAI-API-shlosilon en la linion kun `const API_SHLOSILO = 'sk-...';`.

6. Konservu la skripton per **Ctrl+S** au **Cmd+S** kaj certigu, ke ghi estas aktivigita.

## Uzado

1. Malfermu au aktualigu la deziratan retpaghon.
2. Alklaku **“Komenci”** malsupre dekstre.

Se la butono mankas, kontrolu la permesojn de Tampermonkey kaj eventualajn instruojn pri aktivigo de uzantoskriptoj.

## Atentu

- Sonoj estas sendataj al OpenAI kaj povas enteni personajn informojn.
- API-uzado povas kauzi kostojn.
- **Neniam publikigu vian API-shlosilon**.
- Ne chiuj retejoj kaj menuotipoj estas subtenataj.
