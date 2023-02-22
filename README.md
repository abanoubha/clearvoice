# clearvoice
clear voice : basic processes to clear voice from background hess

```bash
ffmpeg -i <input_file> -af "highpass=f=200, lowpass=f=3000" <output_file>
```
