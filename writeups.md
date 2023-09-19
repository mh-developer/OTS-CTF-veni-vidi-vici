# **Veni vidi vici** writeup

- base64 to image (use some online tool like https://codebeautify.org/base64-to-image-converter)
- `steghide extract -sf downloaded_image.jpg` (maybe is something hide in image, and passphrase is maybe "ots")
- `cat flag` (looks like hex code)
- convert hex to text (use CyberChef "from Hex" option) -> "fwi{vw3j0_1v_u3d11b_6z32rp3}"
- Caesar cipher, key=3 (looks like a flag "fwi{vw3j0_1v_u3d11b_6z32rp3}", we can use online tool to decrypt https://www.dcode.fr/caesar-cipher)

flag: `ctf{st3g0_1s_r3a11y_6w32om3}`
