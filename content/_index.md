---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: slider
    content:
      slides:
      - title: How to build AI systems that behave in accordance with human intentions and values ?
        content: A Survey of Alignment
        align: center
        background:
          image:
            filename: alignment.png
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: How to build AI systems that behave in accordance with human intentions and values ?
        content: A Survey of Alignment
        align: center
        background:
          image:
            filename: alignment2.png
            filters:
              brightness: 0.7
          position: center
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '200px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000


  - block: markdown
    content:
      title: 'The Scope of Alignment'
      subtitle: ''
      text: |
        {{< figure src="diagram-20230916-1.png" caption="The Alignment Cycle. (1) Forward Alignment produces trained systems based on alignment requirements; (2) Backward Alignment ensures the practical alignment of trained systems and revises alignment requirements; (3) The cycle is repeated until reaching a sufficient level of alignment." numbered="false"  width=100% >}}
    design:
      columns: ''
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title: 'Alignment Problem: What, Why and How?'
      subtitle: ''
      text: |

        |Description|Overview|Resource|Updated Date|
        |:---:|:---:|:---:|:---:|
        |Challenges of Alignment|{{< figure src="roadmap.png" width=100% >}}|<ul><li><a href="https://arxiv.org/pdf/2307.15217.pdf">Open problems and fundamental limitations of reinforcement learning from human feedback</a></li><li><a href="https://arxiv.org/pdf/2209.00626.pdf">The alignment problem from a deep learning perspective</a></li></ul>|2023.9.19|

    design:
      columns: ''
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

---