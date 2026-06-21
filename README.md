# http.pokemon

![HTTP Pokémon picture](https://seu-site.com/200)

## About

This is the website that is hosted at [https://seu-site.com](https://seu-site.com).

The project is a Pokémon-themed spiritual successor to the legendary [http.cat](https://http.cat).

This version does not need any complex server-side code. The API behavior is provided by a Vercel server config (`vercel.json`) to handle clean URLs dynamically without extensions, or can be hosted statically on GitHub Pages.

The project uses an automated Python engine to compose, resize, and draw the official pixel-perfect frames.

## Development

Run the image automation engine to process raw images from the input directory:

    python3 frame_composer.py

Customize canvas layout, padding, or compression quality:

    python3 frame_composer.py --width 900 --height 900 --quality 92

## Adding a new image

Currently not all HTTP status codes are covered. You are welcome to create an issue or PR to cover them.

To add a new status:

1. Drop the original image into the `images/` folder (name it exactly as the status code, e.g., `418.png`).
2. Update the `STATUS_NAMES` dictionary inside `frame_composer.py` and the JavaScript mapping file with the correct official status name.
3. Run `python3 frame_composer.py` to compile the new asset into `images_framed/`.

## Credits

Thanks to [http.cat](https://http.cat) and [@rogeriopvl](https://github.com/rogeriopvl) for the original idea and layout inspiration.

Thanks to Nintendo, Game Freak, Creatures Inc., and The Pokémon Company for creating the Pokémon franchise.

#### Thanks to all the contributors:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/alcinoluiz"><img src="https://avatars.githubusercontent.com/u/SEU_ID_DO_GITHUB?v=4?s=100" width="100px;" alt="Seu Nome"/><br /><sub><b>Seu Nome</b></sub></a><br /><a href="https://github.com/alcinoluiz/meu-repositorio/commits?author=SEU_USUARIO" title="Code">💻</a> <a href="#design-SEU_USUARIO" title="Design">🎨</a> <a href="#content-SEU_USUARIO" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=SEU_USUARIO/NOME_DO_REPOSITORIO&type=Date)](https://star-history.com/#SEU_USUARIO/NOME_DO_REPOSITORIO&Date)

## Sponsor / Donate

If you like this project, consider supporting its maintenance:

<a href="https://www.buymeacoffee.com/SEU_USERNAME" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee" height="41" width="174"></a>

## License & Disclaimer

This project is licensed under the MIT License.

**Legal Disclaimer:** This is an open-source, non-commercial fan project. Pokémon and Pokémon character names are trademarks of Nintendo, Creatures Inc., Game Freak, and The Pokémon Company. No copyright infringement is intended. All original assets are generated and distributed for educational and personal use only.# httpoke
