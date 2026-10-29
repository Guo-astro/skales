# Third-Party Notices

Skales bundles content from third-party open-source projects. Each is used under
its own license, reproduced below. This file satisfies the attribution
requirement of those licenses; in addition, every bundled item carries its
author, source, and license inline (in the app UI and in each file's metadata).

---

## Built-in Agent Skills — mattpocock/skills

The built-in Agent Skills library bundled with Skales adapts skills from
**mattpocock/skills** (https://github.com/mattpocock/skills), used under the
MIT License. Each skill's `SKILL.md` frontmatter records `author: Matt Pocock`,
`source: mattpocock/skills`, and `license: MIT`.

The upstream `deprecated/` and `in-progress/` buckets are not bundled (upstream
marks them as unshipped), and `setup-matt-pocock-skills` is omitted (it scaffolds
a repo layout specific to the upstream distribution, not applicable in Skales).

```
MIT License

Copyright (c) 2026 Matt Pocock

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Design Style-Packs — VoltAgent/awesome-design-md

The design style-packs bundled with Skales adapt DESIGN.md styleguides from
**VoltAgent/awesome-design-md**
(https://github.com/VoltAgent/awesome-design-md), used under the MIT License.
Each pack is presented in the UI as an "inspired by" aesthetic reference with
its source (VoltAgent/awesome-design-md) and license (MIT). Packs carry no
logos or trademarks; Skales renders none, and honouring any brand's trademark
rights is the user's responsibility.

```
MIT License

Copyright (c) 2026 VoltAgent

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Bundled typefaces - Inter, Space Grotesk, DM Sans, JetBrains Mono, Lora, Caveat, Comic Neue, Noto Color Emoji

Skales bundles eight typefaces, each used under the
**SIL Open Font License 1.1**. They are shipped with the app rather than fetched
at runtime so a packaged, offline install renders the real type instead of a
system fallback, and so no page load reaches a font CDN.

- **Inter** (https://github.com/rsms/inter), Copyright (c) 2016 The Inter Project Authors
- **Space Grotesk** (https://github.com/floriankarsten/space-grotesk), Copyright (c) 2020 Florian Karsten
- **DM Sans** (https://github.com/googlefonts/dm-fonts), Copyright (c) 2014-2024 Colophon Foundry, Jonny Pinhorn, Indian Type Foundry
- **JetBrains Mono** (https://github.com/JetBrains/JetBrainsMono), Copyright (c) 2020 The JetBrains Mono Project Authors
- **Lora** (https://github.com/cyrealtype/Lora-Cyrillic), Copyright 2011 The Lora Project Authors, with Reserved Font Name "Lora" - a chat-bubble face offered under Settings > Appearance
- **Caveat** (https://github.com/googlefonts/caveat), Copyright 2014 The Caveat Project Authors - a chat-bubble face offered under Settings > Appearance
- **Comic Neue** (https://github.com/crozynski/comicneue), Copyright 2014 The Comic Neue Project Authors - a chat-bubble face offered under Settings > Appearance
- **Noto Color Emoji** (https://github.com/googlefonts/noto-emoji), Copyright (c) Google Inc. - shipped as the COLRv1 build so every emoji in the app renders the same on a machine that has no colour emoji font of its own

The subset files are the ones Google Fonts serves, unmodified; only the file
names differ. The OFL permits bundling and redistribution with the application;
none of the fonts is sold on its own, and no Reserved Font Name is used for a
modified version.

```
SIL OPEN FONT LICENSE Version 1.1

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide development
of collaborative font projects, to support the font creation efforts of academic
and linguistic communities, and to provide a free and open framework in which
fonts may be shared and improved in partnership with others.

The OFL allows the licensed fonts to be used, studied, modified and redistributed
freely as long as they are not sold by themselves. The fonts, including any
derivative works, can be bundled, embedded, redistributed and/or sold with any
software provided that any reserved names are not used by derivative works. The
fonts and derivatives, however, cannot be released under any other type of
license. The requirement for fonts to remain under this license does not apply to
any document created using the fonts or their derivatives.

PERMISSION & CONDITIONS
Permission is hereby granted, free of charge, to any person obtaining a copy of
the Font Software, to use, study, copy, merge, embed, modify, redistribute, and
sell modified and unmodified copies of the Font Software, subject to the
following conditions:

1) Neither the Font Software nor any of its individual components, in Original or
Modified Versions, may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled,
redistributed and/or sold with any software, provided that each copy contains the
above copyright notice and this license. These can be included either as
stand-alone text files, human-readable headers or in the appropriate
machine-readable metadata fields within text or binary files as long as those
fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font Name(s)
unless explicit written permission is granted by the corresponding Copyright
Holder. This restriction only applies to the primary font name as presented to
the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font Software
shall not be used to promote, endorse or advertise any Modified Version, except
to acknowledge the contribution(s) of the Copyright Holder(s) and the Author(s)
or with their explicit written permission.

5) The Font Software, modified or unmodified, in part or in whole, must be
distributed entirely under this license, and must not be distributed under any
other license. The requirement for fonts to remain under this license does not
apply to any document created using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT, PATENT, TRADEMARK, OR
OTHER RIGHT. IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL,
OR CONSEQUENTIAL DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER
DEALINGS IN THE FONT SOFTWARE.
```

---

## Noto Emoji 3D and animated — CC BY 4.0

The animated emoji Skales plays in chat, and the 3D emoji artwork it shows
beside them, come from Google's **Noto Emoji** projects
(https://github.com/googlefonts/noto-emoji and
https://github.com/googlefonts/noto-emoji-animation), used under the
**Creative Commons Attribution 4.0 International** licence
(https://creativecommons.org/licenses/by/4.0/).

This is a redistribution, not a hotlink, and that is why the attribution is
carried here and shown inside the app rather than left to the upstream site:
the Lottie files are served from Skales' own relay
(`relay.skales.app/emojis/<codepoint>/lottie.json`), and Google's CDN is only a
fallback the user can switch on. CC BY 4.0 asks for the name of the creator,
the source and the licence wherever the material appears, so all three travel
with every copy of the app.

- Creator: **Google** (the Noto Emoji authors)
- Source: `googlefonts/noto-emoji`, `googlefonts/noto-emoji-animation`
- Licence: CC BY 4.0, link above
- Changes: none to the artwork. The files are mirrored unmodified; only the
  hosting address differs.

Noto is a trademark of Google LLC. The typeface and the artwork are licensed;
the name is not. See TRADEMARK.md.

---

## Local speech — sherpa-onnx, Whisper, and the Piper voices

Skales Local's on-device speech is built on **sherpa-onnx**
(https://github.com/k2-fsa/sherpa-onnx), used under the Apache License 2.0. The
`sherpa-onnx-node` package and its platform binaries are shipped unmodified,
except for one packaging repair: `install_name_tool -add_rpath @loader_path` is
applied to `sherpa-onnx.node` on macOS, because the published binary carries the
build machine's own directory as its only rpath and cannot otherwise find the
libraries beside it. No source is changed.

Speech to text uses **Whisper** (https://github.com/openai/whisper), MIT
licensed in both code and weights, in the int8 ONNX conversions published by the
sherpa-onnx project.

Text to speech uses **Piper voices** for most languages, a **Coqui VITS** model
for Croatian and an **icefall VITS** model for Chinese. A note on the Piper ones,
because the distinction is load-bearing: Piper's own code (OHF-Voice/piper1-gpl)
is licensed GPL-3.0 and is **not** linked, imported, vendored or shipped by
Skales. What Skales downloads is the voice files (`.onnx`), which are read by
sherpa-onnx.

Each voice carries its own licence, recorded per entry in the model catalogue
and shown on the model card in Settings before the download starts. The licences were read out of each
published archive rather than taken from a list of recommended voices, and that
mattered in both directions: six candidate voices were EXCLUDED on those grounds
(three are CC-BY-NC-SA, two declare no licence at all, one is research-only) and
one - the Croatian voice - was very nearly excluded for the opposite reason, its
sherpa packaging carrying no licence file while the Coqui manifest it is built
from and its author's own model card both state BSD-3-Clause.

No model files are bundled with the application. They are downloaded, on
request, from the upstream release the catalogue names, directly to the user's
machine.

---

## Agent prompts - msitarzewski/agency-agents

Several built-in agents, team presets and organization templates run on
specialist prompts from **agency-agents** (https://github.com/msitarzewski/agency-agents),
used under the MIT License. The library is bundled as published; the prompts an
agent runs with are its Markdown bodies with emoji removed and a short Skales
block appended (the name the agent appears under, its part in the team, and the
rule to answer in the user's language). Every card whose prompt comes from the
library says so ("Prompt: agency-agents (MIT)") and links to the source file.
The upstream commit is recorded next to the bundled files.

```
MIT License

Copyright (c) 2025 AgentLand Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Skill packs - rewritten from open-source skills

Some built-in Agent Skills are Skales' own rewrites of open-source skills. Skales read the sources, took
facts, methods and API details, and wrote new text in its own words and structure; no source text ships
in the app. Each such skill names its sources on its card ("rewritten by Skales from ...") and in its
file (metadata.rewrittenFrom). The sources, the commit each rewrite was made from, and their licences:

| Skill | Source | Commit | Licence |
|---|---|---|---|
| frontend-design | Leonxlnx/taste-skill (https://github.com/Leonxlnx/taste-skill) | ce26fc25c0e5 | MIT |
| frontend-design | pbakaus/impeccable (https://github.com/pbakaus/impeccable) | 9d715cc4f556 | Apache-2.0 |
| motion-design | heygen-com/hyperframes (https://github.com/heygen-com/hyperframes) | b165b64eda84 | Apache-2.0 |
| motion-design | latent-spaces/brag (https://github.com/latent-spaces/brag) | c893c5ed52ae | MIT |
| motion-design | LottieFiles/motion-design-skill (https://github.com/LottieFiles/motion-design-skill) | f9a8a041b851 | MIT |
| office-docs | MiniMax-AI/skills (https://github.com/MiniMax-AI/skills) | 60aaae52bb2a | MIT |
| office-docs | zarazhangrui/frontend-slides (https://github.com/zarazhangrui/frontend-slides) | 9906a34d640d | MIT |
| video-schnitt-shortform | digitalsamba/claude-code-video-toolkit (https://github.com/digitalsamba/claude-code-video-toolkit) | 225c80a1c3a5 | MIT |
| video-schnitt-shortform | heygen-com/hyperframes (https://github.com/heygen-com/hyperframes) | b165b64eda84 | Apache-2.0 |

### digitalsamba/claude-code-video-toolkit - MIT

```
MIT License

Copyright (c) 2024 Digital Samba

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### latent-spaces/brag - MIT

```
MIT License

Copyright (c) 2026 Shunit Haviv Hakimi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Leonxlnx/taste-skill - MIT

```
MIT License

Copyright (c) 2026 Leonxlnx

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### LottieFiles/motion-design-skill - MIT

```
MIT License

Copyright (c) 2025 LottieFiles

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### MiniMax-AI/skills - MIT

```
MIT License

Copyright (c) 2026 MiniMax

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### zarazhangrui/frontend-slides - MIT

```
MIT License

Copyright (c) 2025 Zara Zhang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### heygen-com/hyperframes, pbakaus/impeccable - Apache-2.0

The skills rewritten from these sources are modified works: their text was written anew by Skales.

heygen-com/hyperframes: Copyright 2026 HeyGen, Inc.

pbakaus/impeccable: Copyright 2025 Paul Bakaus

NOTICE of pbakaus/impeccable:

```
# Third-Party Notices

This project includes content derived from third-party work, used under the terms of its original license.

## Platform Design Skills

The `skill/reference/ios.md` and `skill/reference/android.md` platform reference files are distilled from ehmo's `platform-design-skills` (Apple Human Interface Guidelines and Material Design 3 rules), rewritten in Impeccable's voice.

**Original work:** https://github.com/ehmo/platform-design-skills
**Original license:** MIT
**Author:** ehmo
```

```
Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to the Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by the Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding any notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   Copyright 2026 HeyGen, Inc.

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

---

## JavaScript source parser — Acorn

Skales uses **Acorn 8.16.0** (https://github.com/acornjs/acorn) to inspect
authored motion JavaScript without running it. Acorn is used under the MIT
License, reproduced below.

```
MIT License

Copyright (C) 2012-2022 by various contributors (see AUTHORS)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

## Scout live picture viewer - noVNC

Skales uses **noVNC 1.7.0** (https://github.com/novnc/noVNC) to show the live
picture of a Scout's computer inside the app. The noVNC core library is used
unmodified, as published on npm as `@novnc/novnc`, under the Mozilla Public
License 2.0 (https://www.mozilla.org/MPL/2.0/). Its source code is available
at https://github.com/novnc/noVNC/tree/v1.7.0 and in the npm package itself.
Files vendored by noVNC keep their own licences (pako: MIT). The full licence
texts ship with the package (`docs/LICENSE.MPL-2.0`, `vendor/pako/LICENSE`)
and are listed with the other components in the About screen.

noVNC is Copyright (C) 2022 The noVNC authors.

---

## Scout workspace image and VM components

The Scout workspace is a separate disk image that Skales downloads on request
and runs as its own virtual machine next to Skales. It is built on Debian
(Debian 13, packages from the Debian `main` archive only) and contains free
software under the GNU General Public License (GPL), the GNU Lesser General
Public License (LGPL) and other licences, among them the Linux kernel,
systemd, Chromium, Python, Node.js and git. On Windows, Skales additionally
ships QEMU to run that image, and on Linux, Cloud Hypervisor (Apache License
2.0 and BSD 3-Clause), unmodified and as its own program. On macOS each Scout
VM runs inside skales-vmd, Skales' own helper, which includes Code-Hex/vz and
go-infinity-channel (MIT) and the Go standard library and golang.org/x/mod
(BSD 3-Clause); their licence texts are listed with the other components
below. Each component keeps its own copyright notice
and licence text inside the image (`/usr/share/doc/<package>/copyright` and
`/usr/share/common-licenses/`), and every image release carries the list of
packages with their versions and licences.

The workspace image and QEMU contain free software under GPL, LGPL and other
licences. The complete source code of these components is published with each
image version, in the same release as the image:
https://github.com/skalesapp/skales/releases (releases named
`scout-image-v<version>`: the `sources` parts and `SOURCES.txt`). The Debian
snapshot the image was built from is named in each release as well.

Third-party components are under their own licences. The Skales `LICENSE`,
`LICENSE.de` and `TRADEMARK.md` do not apply to them, and nothing in this
section is a statement about the licence of Skales itself. Debian is a
registered trademark of Software in the Public Interest, Inc.; Skales is not
affiliated with or endorsed by the Debian project.
