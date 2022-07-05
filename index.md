# RAVE Source Separation with DSD100/MUSDB18 Sound Examples

This site contains a couple of sound examples of the song "Water Duct" by Ava Luna. 
The song is from the test set (songs from MUSDB18 not included in DSD100)l, chosen because of the intro with a clear bass and drums and later on changing up the beat.

## Original and Reconstruction
The original song in Mono and 16 kHz (since the RAVE model was trained at 16 kHz), alongside the modified model reconstruction and the unmodified model reconstruction (which has trained only on full mixes).

[Original Mono](/ORIGINAL_RAVE_RECON.wav?raw=true)

[Original Mono 16 kHz](/ORIGINAL_RAVE_RECON.wav?raw=true)

[Modified Model Reconstruction](/ORIGINAL_RAVE_RECON.wav?raw=true)


[Unmodified Model Reconstruction](/ORIGINAL_RAVE_RECON.wav?raw=true)


## Source Separation

The full mix is input to the modified model and all partitions except one is replaced with encoded silence.
The high-variance dimensions are left intact.

[Partition 0 (Other)](/ORIGINAL_RAVE_RECON.wav?raw=true)

[Partition 1 (Vocals)](/ORIGINAL_RAVE_RECON.wav?raw=true)

[Partition 2 (Drums)](/ORIGINAL_RAVE_RECON.wav?raw=true)

[Partition 3 (Bass)](/ORIGINAL_RAVE_RECON.wav?raw=true)


## High Variance Dimension Examples

The modified model has three high-variance dimensions that do not conform with to the source partitions.
These are some examples of these dimensions being offset, set, amplified and inverted.

### Dim 33

### Dim 42

### Dim 75


## 

[elephant](/ORIGINAL_RAVE_RECON.wav?raw=true)

 <iframe src="/ORIGINAL_RAVE_RECON.wav" allow="autoplay" style="display:none" id="iframeAudio"></iframe>
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/vidret/Embedding-Loss-Examples/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
