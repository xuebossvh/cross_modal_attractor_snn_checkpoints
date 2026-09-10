# cross_modal_attractor_snn checkpoints

Checkpoint files exported from local outputs/checkpoints.

Total size: 7.07 GiB (36 checkpoint files)

Files:
- cross_modal_snn.pt (40.2 MB)
- cross_modal_snn_v10a.pt (256.1 MB)
- cross_modal_snn_v10b.pt (256.1 MB)
- cross_modal_snn_v10c.pt (256.1 MB)
- cross_modal_snn_v10d.pt (257.1 MB)
- cross_modal_snn_v10e.pt (257.8 MB)
- cross_modal_snn_v10f.pt (257.8 MB)
- cross_modal_snn_v11a.pt (259.5 MB)
- cross_modal_snn_v11a_control.pt (258.3 MB)
- cross_modal_snn_v11b.pt (212.9 MB)
- cross_modal_snn_v11b_control.pt (211.8 MB)
- cross_modal_snn_v11b_cross_no_causal.pt (212.9 MB)
- cross_modal_snn_v11b_decoder_pretrain.pt (86.9 MB)
- cross_modal_snn_v11b_recovery_ep100.pt (258.3 MB)
- cross_modal_snn_v11b_recovery.pt (258.3 MB)
- cross_modal_snn_v11b_weighted.pt (258.3 MB)
- cross_modal_snn_v11c.pt (212.9 MB)
- cross_modal_snn_v11c_control.pt (211.8 MB)
- cross_modal_snn_v11d.pt (217.1 MB)
- cross_modal_snn_v11d_control.pt (213.9 MB)
- cross_modal_snn_v11e.pt (258.9 MiB)
- cross_modal_snn_v11e_control.pt (257.7 MiB)
- cross_modal_snn_v11f.pt (87.5 MiB)
- cross_modal_snn_v11f_no_causal.pt (87.5 MiB)
- cross_modal_snn_v2.pt (61.1 MB)
- cross_modal_snn_v3.pt (61.1 MB)
- cross_modal_snn_v4.pt (61.1 MB)
- cross_modal_snn_v6a.pt (207.7 MB)
- cross_modal_snn_v6b.pt (89.3 MB)
- cross_modal_snn_v6c.pt (206.6 MB)
- cross_modal_snn_v7.pt (206.6 MB)
- cross_modal_snn_v8.pt (219.8 MB)
- cross_modal_snn_v9.pt (233.8 MB)
- cross_modal_snn_v9a.pt (233.8 MB)
- cross_modal_snn_v9b.pt (256.1 MB)
- cross_modal_snn_v9c.pt (256.1 MB)

The `.pt` files are stored with Git LFS. Clone with Git LFS installed, then run
`git lfs pull` to download the checkpoint contents.

## SHA-256 for v11 checkpoints

| File | SHA-256 |
|---|---|
| `cross_modal_snn_v11b_recovery.pt` | `65a7c56aab1c4155cfb34ae6d16cbf4e94bb82bc9d2c945f08d6e7a8f0120b0e` |
| `cross_modal_snn_v11c.pt` | `0e7333b5f9f3983c0637278e0c1b304388d192ea2527445995643df5a74db3af` |
| `cross_modal_snn_v11c_control.pt` | `ba73371e70558ef0e3a91a590591380aa3d2c5c1cede038d08601470786a1503` |
| `cross_modal_snn_v11d.pt` | `fd65dadd0f0c7062433d38fb06a9def4690cc174b27e7936c9d645fccd5486ea` |
| `cross_modal_snn_v11d_control.pt` | `46dc0b044d14f17c87279d9ddc70b18f1f527b1fc0a8f4f97a9fc98347ffef01` |
| `cross_modal_snn_v10a.pt` | `8bdffe55abec243e6f632df6ad11ae138744ada0c87f9cc0b04c77735a2c943a` |
| `cross_modal_snn_v10b.pt` | `a2eb15205db3f376ff89bbb45106056db804112902af3340d73d7a4f5571bb6b` |
| `cross_modal_snn_v10c.pt` | `b84e0a741c2f217538fe596431fa04903157bdaee5db6fca6c0159e27fc06e48` |
| `cross_modal_snn_v10d.pt` | `f171dcec56217f8011c8b446f92970dfc20adebfa7b37b6da66c89eaf002c1df` |
| `cross_modal_snn_v10e.pt` | `8f53c8cfa193e8fde3bcb0be70a84bd33fc61883832dcd35402e93be80905757` |
| `cross_modal_snn_v10f.pt` | `8476d9328ecacefce7bbe09286126ed7bb3ecd6bec524421ab70e40fef089c6c` |
| `cross_modal_snn_v11a.pt` | `48821aa3ad0812a53a5366b7beea3603812ba2210639ae7da04d6dd93a160066` |
| `cross_modal_snn_v11a_control.pt` | `d5f832c5160ed432a273139b2729990f4f353dc0b41dac04eb1531b52b23fc77` |
| `cross_modal_snn_v11b.pt` | `90955a762f9b4a0929a8245493a8a5a8307302e651e00aabbfc0f7919d0ba3ad` |
| `cross_modal_snn_v11b_control.pt` | `859a4c2ae6612265da40176fb5973d337bf6e10edf036ec719199edc945a281f` |
| `cross_modal_snn_v11b_cross_no_causal.pt` | `3da9d494c2fa8c46ac53653c6f8e28997a75e56804a4941b316932874cc799e1` |
| `cross_modal_snn_v11b_decoder_pretrain.pt` | `05515ac956fbc4319084329193556195d20adf83f2171625c547681e58379554` |
| `cross_modal_snn_v11b_recovery_ep100.pt` | `25730624ef654d1f7d178a6bdbe64e85ccf20765529ed852a056790c8ba078c7` |
| `cross_modal_snn_v11b_weighted.pt` | `7be817000b435a7943d3c6221f998f754bc89d5d0962b41aef96fa9135196622` |

## v11f checkpoints (2026-09-10)

Both v11f runs completed 30 additional epochs (`epoch=29`) from the same
100-epoch v11e control (`epoch=99`). Each contains the full model state and
48,736 adapter parameters, not only an adapter delta. The smaller files reflect
the adapter-only optimizer state, not a missing backbone.

| File | Bytes | SHA-256 |
|---|---:|---|
| `cross_modal_snn_v11f.pt` | 91702478 | `9b3c2a6fc47f6cb890c2cfd0a87564ce612e5b8424ef343607da8dfef1d95fc8` |
| `cross_modal_snn_v11f_no_causal.pt` | 91704486 | `3951fadc830c0583a73e93340bc1906da5c7578544d478680fec990ace01359f` |
| `cross_modal_snn_v11e_control.pt` (existing parent) | 270261261 | `5a792f10e57a95947c8e51bd915b09897baee01475103010826f25275b71501b` |

All non-adapter parameters and buffers were compared with the parent and found
bitwise identical. Recomputed base-state SHA-256:
`92b2f7d6d2127376d59ba093ab86c787a34d6efb038b7e0054ebdbe5489fc02a`.
Evaluation code/configs and the analysis report belong to the code repository's
`v11f` branch. `v11f_control` uses the existing parent file; no separate control
checkpoint is expected.
