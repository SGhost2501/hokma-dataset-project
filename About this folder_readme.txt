:

📂 Hokma Dataset Project Folder
This folder is designed to house all files needed to generate and refine a large language model (LLM) dataset for simulating Hokma (from Project Moon / Lobotomy Corporation).

📌 Main contents
1️⃣ Abnormality data files

all_abnos.jsonl → structured list of abnormalities (name, classification, attack type, E-boxes, Qliphoth counter)

all abnos.txt → original unstructured abnormalities list

2️⃣ Prompt files

abnormality_prompts.jsonl → prompts generated about abnormalities, ready for LLM use

abnormality_prompts_enriched.jsonl → prompts + enriched outputs (with classification and attack info)

3️⃣ Scripts

generate_abno_prompts.py → generates input/output pairs with metadata

convert_abnos_to_jsonl.py → converts unstructured abno list into JSONL format

4️⃣ Supporting files

Hokma_LLM_Master_Summary.txt → summary of dataset goals and structure

Additional notes files (e.g. summaries, suppression info, guest lists, locations) that inform lore

📌 Purpose of the folder
✅ To support creating a clean, structured, and lore-accurate dataset that can:

Generate 2000+ input/output pairs simulating Hokma’s speech

Provide both question prompts and thoughtful, Hokma-like answers

Contain metadata for fine-tuning and filtering

Ensure variety and balance in topics (moral, procedural, classification, handling, philosophical)

