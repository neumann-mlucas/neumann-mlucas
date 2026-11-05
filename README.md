### Hi, I'm Lucas

Backend engineer working where finance meets infrastructure. By day I keep pricing and risk systems honest: Bloomberg MARS pipelines, real-time market-data and curve services, and Go + MCP tooling that lets LLM agents poke at production data without breaking anything.

I came in sideways: my MSc was protein simulations on HPC clusters, and at some point the code got more interesting than the chemistry.

```fortran
      PROGRAM LUCAS
C     NO DERIVED TYPES IN 1977, SO PARALLEL ARRAYS IN A COMMON BLOCK.
      CHARACTER*48 BASE
      CHARACTER*16 JOB(4), STACK(6), FUN(5)
      CHARACTER*25 PREV(3)
      COMMON /ENGR/ BASE, JOB, STACK, FUN, PREV
      DATA BASE /'SAO PAULO, BR (REMOTE / RELOCATION OK)'/
      DATA JOB /'PRICING', 'RISK', 'MARKET DATA', 'AI-AGENT TOOLING'/
      DATA STACK /'PYTHON', 'GO', 'SQL', 'AIRFLOW',
     &            'KUBERNETES', 'AWS'/
      DATA FUN /'RUST', 'JULIA', 'HASKELL', 'NEOVIM PLUGINS',
     &          'GENERATIVE ART'/
      DATA PREV /'BANK OF AMERICA (FICC EM)', 'APEX CAPITAL',
     &           'MSC PHYS. CHEM. @ UNICAMP'/
      WRITE (*,'(A)') BASE
      END
```

Off the clock it's Rust, Julia and the occasional Haskell, all written in Neovim, which I configure more than I should and sometimes write plugins for.

Daily driver: Arch + Hyprland + Ghostty + Neovim, all of it in [dotfiles](https://github.com/neumann-mlucas/dotfiles).

#### Things I build for fun

- [**git-archaeologist**](https://github.com/neumann-mlucas/git-archaeologist) (Rust): digs time series out of any git repo, like LOC, cohort survival, coupling and hotspots.
- [**ragwatcher**](https://github.com/neumann-mlucas/ragwatcher) (Python): local, incremental RAG over a folder, served as an MCP tool.
- [**StringArt.jl**](https://github.com/neumann-mlucas/StringArt.jl) and [**MonteCarloArt.jl**](https://github.com/neumann-mlucas/MonteCarloArt.jl) (Julia): turn photos into string art and pointillism.
- [**snacks-lexicon.nvim**](https://github.com/neumann-mlucas/snacks-lexicon.nvim) (Lua): dictionary and thesaurus lookups without leaving Neovim.
- **visidata-rs** (Rust, WIP): rebuilding a terminal data explorer on Polars + Ratatui, scriptable in Lua.
- Advent of Code in [Haskell](https://github.com/neumann-mlucas/advent_of_code_2020), [Go](https://github.com/neumann-mlucas/advent_of_code_2023) and [Julia](https://github.com/neumann-mlucas/advent_of_code_2024).

#### CV

[web](https://neumann-mlucas.github.io/cv) · PDF [EN](https://github.com/neumann-mlucas/cv/raw/main/pdf/cv-en-tech.pdf) / [PT](https://github.com/neumann-mlucas/cv/raw/main/pdf/cv-pt-tech.pdf) · [LinkedIn](https://www.linkedin.com/in/lucas-mneumann/)

Generated from one YAML file with Typst; the source is in [neumann-mlucas/cv](https://github.com/neumann-mlucas/cv).
