# RAVE Source Separation with DSD100/MUSDB18 Sound Examples

This site contains a couple of sound examples of the song "Water Duct" by Ava Luna. 
The song is from the test set (songs from MUSDB18 not included in DSD100)l, chosen because of the intro with a clear bass and drums alongside some variation in rhythm later in the song. The modified model is with regularization strength γ=10.

## Original and Reconstruction
The original song in Mono and 16 kHz (since the RAVE model was trained at 16 kHz), alongside the modified model reconstruction and the unmodified model reconstruction (which has trained only on full mixes).

[Original Mono](/Mixture-mono.mp3?raw=true)

[Original Mono 16 kHz](/Mixture-mono-16k.mp3?raw=true)

[Modified Model Reconstruction](/MOD_STRONG_RECON.mp3?raw=true)

[Unmodified Model Reconstruction](/ORIGINAL_RAVE_RECON.mp3?raw=true)


## Source Separation

The full mix is input to the modified model and all partitions except one is replaced with encoded silence.
The high-variance dimensions are left intact.

[Partition 0 (Other)](/MOD_ONLY_ONE_PARTITION_part0_mixture.mp3?raw=true)

[Partition 1 (Vocals)](/MOD_ONLY_ONE_PARTITION_part1_mixture.mp3?raw=true)

[Partition 2 (Drums)](/MOD_ONLY_ONE_PARTITION_part2_mixture.mp3?raw=true)

[Partition 3 (Bass)](/MOD_ONLY_ONE_PARTITION_part3_mixture.mp3?raw=true)


## High Variance Dimension Examples

The modified model has three high-variance dimensions that do not conform with to the source partitions.
These are some examples of these dimensions being offset, set, amplified and inverted.

### Dim 33

[Amplified 3.0](/MOD_STRONG_RECON_DIM33_attenuvert_3.0.mp3?raw=true)

[Inverted/Amplified -3.0](/MOD_STRONG_RECON_DIM33_attenuvert_-3.0.mp3?raw=true)

[Offset 2.0](/MOD_STRONG_RECON_DIM33_offet_2.0.mp3?raw=true)

[Offset -2.0](/MOD_STRONG_RECON_DIM33_offet_-2.0.mp3?raw=true)

[Set 1.0](/MOD_STRONG_RECON_DIM33_set_1.0.mp3?raw=true)

[Set -1.0](/MOD_STRONG_RECON_DIM33_set_-1.0.mp3?raw=true)


### Dim 42

[Amplified 3.0](/MOD_STRONG_RECON_DIM42_attenuvert_3.0.mp3?raw=true)

[Inverted/Amplified -3.0](/MOD_STRONG_RECON_DIM42_attenuvert_-3.0.mp3?raw=true)

[Offset 2.0](/MOD_STRONG_RECON_DIM42_offet_2.0.mp3?raw=true)

[Offset -2.0](/MOD_STRONG_RECON_DIM42_offet_-2.0.mp3?raw=true)

[Set 1.0](/MOD_STRONG_RECON_DIM42_set_1.0.mp3?raw=true)

[Set -1.0](/MOD_STRONG_RECON_DIM42_set_-1.0.mp3?raw=true)

### Dim 75

[Amplified 3.0](/MOD_STRONG_RECON_DIM75_attenuvert_3.0.mp3?raw=true)

[Inverted/Amplified -3.0](/MOD_STRONG_RECON_DIM75_attenuvert_-3.0.mp3?raw=true)

[Offset 2.0](/MOD_STRONG_RECON_DIM75_offet_2.0.mp3?raw=true)

[Offset -2.0](/MOD_STRONG_RECON_DIM75_offet_-2.0.mp3?raw=true)

[Set 1.0](/MOD_STRONG_RECON_DIM75_set_1.0.mp3?raw=true)

[Set -1.0](/MOD_STRONG_RECON_DIM75_set_-1.0.mp3?raw=true)

