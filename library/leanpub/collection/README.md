# Leanpub — Drive Collection intake (2026-10-08)

**Source:** https://drive.google.com/drive/folders/15JBUJobAhiEEb7IZDDcU0_5gwnlZWUJw  
**Standing:** Architect-designated **NON-CANONICAL** within the Library; intake receipt only.  
**Location:** `library/leanpub/collection/`

All **seven** files in the specified Drive Collection are preserved here. **Six** are exact source-byte Git files. The seventh PDF is present as **five ordered binary parts** due to a large-file upload transport limitation, not as one directly viewable PDF. Source digests below refer to the exact original Drive PDFs.

| Original Drive filename | Drive file ID | Original SHA-256 | Representation |
| --- | --- | --- | --- |
| `Field-Guide` | `1WRPBw2f51d1ELsfxKhf3U1P3t17GYpyE` | `5395289d24b6e3624cc4202a3d4a496b9f6a79da5a9808581bee8c0a93799ee4` | Direct file |
| `Documentation-Epistemic-Apertures_Harmonia-View.pdf` | `1nQYXhS7sRIKxWLL8-awDJFaNljndx6-e` | `95e346b50d23fc6c215c8626b2d63a9286356c20efc4d755bf16026aabee3470` | Direct file |
| `Integral.pdf` | `1YBuOHXEkObz4G-7MG9n0d98W_qac-o8w` | `ed60ca92af44e4fe335fcfe78a8ba8b52f2aca47d3183be17b78c728282e5ae2` | Direct file |
| `Substantive.pdf` | `1b6982RojVVzEZNZPsoUxhXZHAQ9JAUv1` | `739ece92c608c25cd63fee2f1a9a21f3dc31f1ac7086ef0ee37942d254c1c9ba` | Direct file |
| `Substantial.pdf` | `1z1vVQefuVXmShb5WvxjbCDj5TQNlFpy1` | `d229c17aa2f4fc24ac18ec695f89e2a4438c005572ce4493b2503dad320117db` | Direct file |
| `Contemplation.pdf` | `1szMUWbl748Gs7yjNH6Hx19rwY2e2AuXG` | `8a0a37b14184bfd20403b8a09375a4751cef9c349837e5ed00c2e4c7a2a0bb47` | Direct file |
| `Epistemology-Equanimity_Harmonia-View.pdf` | `1aj7Q99Ou7US1VVvGMvLKuhbnH0ZSYege` | `3e2d0f56834efd58107a7f374e7b012a969274bd1cda40a75dd00dc471b969a6` | Five parts in [`_parts/`](_parts/) |

**Filename:** `Field-Guide` is a PDF (Drive MIME `application/pdf`) whose original filename has no extension. The name is deliberately preserved.

## Reassemble the seventh PDF

The parts of `Epistemology-Equanimity_Harmonia-View.pdf` are exact contiguous original-byte segments:

| Part | Bytes | Part SHA-256 |
| --- | ---: | --- |
| `_parts/Epistemology-Equanimity_Harmonia-View.pdf.part001` | 786432 | `3b644dd1425b194768be0b27db9e14325f5d382eb97ae90bd21cc2bcfe92cf3b` |
| `_parts/Epistemology-Equanimity_Harmonia-View.pdf.part002` | 786432 | `964dbd79c38dd61a725372bc40a37154e8564a9cbaabae682b03010e85ae6805` |
| `_parts/Epistemology-Equanimity_Harmonia-View.pdf.part003` | 786432 | `f423d579c575925412f940d7a7cd7108c7b7b25624f9fc36888f15c4f051a967` |
| `_parts/Epistemology-Equanimity_Harmonia-View.pdf.part004` | 589824 | `904396a2ddeb25890c66a7815ece444c62478ef4855074d2539d11b502ce6318` |
| `_parts/Epistemology-Equanimity_Harmonia-View.pdf.part005` | 199554 | `f3237be64e928fa1f5536d9a8f1c1448e7a12b3b60887efe45ede3a407f8a60f` |

From the repository root on a local checkout:

```sh
cat library/leanpub/collection/_parts/Epistemology-Equanimity_Harmonia-View.pdf.part00{1,2,3,4,5} > Epistemology-Equanimity_Harmonia-View.pdf
sha256sum Epistemology-Equanimity_Harmonia-View.pdf
```

Expected total original bytes: **3,148,674**. Expected SHA-256: `3e2d0f56834efd58107a7f374e7b012a969274bd1cda40a75dd00dc471b969a6`.

This is **source-preservation**, not proof of an edition currently published through Leanpub, completion, a formal seal, or canonical standing. The existing *Contemplation* shoreline branding remains unchanged. This set is separate from the earlier sample PDFs and cover.
