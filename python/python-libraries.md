# Python Libraries (Practical Stack)

Simple, fast, and powerful tools for modern Python development.

---

## Core

* **pydantic**  
  Data validation and structured schemas (great for APIs & LLM outputs)  
  https://docs.pydantic.dev/

* **typer**  
  Build clean and fast CLI applications  
  https://typer.tiangolo.com/

* **rich**  
  Beautiful terminal output (colors, tables, progress bars)  
  https://rich.readthedocs.io/

* **requests**  
  Simple HTTP requests (APIs, downloads)  
  https://requests.readthedocs.io/

* **loguru**  
  Easy and readable logging  
  https://loguru.readthedocs.io/

---

## Data & Files

* **polars**  
  High-performance DataFrame (Rust-based, very fast)  
  https://pola.rs/

* **pillow**  
  Basic image processing (resize, convert formats)  
  https://pillow.readthedocs.io/

* **markitdown**  
  Convert PDF, Word, Excel, images → clean Markdown  
  Perfect for LLM pipelines  
  https://github.com/microsoft/markitdown

  ## Automation & AI Tools

### Automation

* **tenacity**  
  Smart retry system for unstable API calls  
  https://tenacity.readthedocs.io/  
  Helps automatically retry failed requests with backoff logic, especially useful for APIs and network operations.

---

### AI & Local

* **ollama**  
  Run AI models locally (no cloud needed)  
  https://ollama.com/  
  Lets you run large language models directly on your machine for private and fast AI workflows.

* **smolagents**  
  Lightweight LLM agents for fast prototyping  
  https://github.com/huggingface/smolagents  
  Simple framework for building AI agents quickly without heavy setup.

```bash
uv pip install "markitdown[all]"
