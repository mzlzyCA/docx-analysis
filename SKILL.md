---
name: docx-analysis
version: 0.2.0
description: >
  Analyze DOCX document structure, content, metadata, and formatting with precision using MinerU-powered parsing. Extract headings, paragraphs, styles, embedded images, tables, footnotes, and document properties from Microsoft Word files. DOCX文档分析, Word文件结构分析, Word文档解析, 文档元数据提取.

  Supports .docx inspection, Word document analysis, document structure extraction, content parsing, metadata reading, style analysis, formatting audit, XML structure inspection, document property extraction, and Office Open XML analysis.

  Use when asked to "analyze this Word document", "what's inside this DOCX file", "extract metadata from Word file", "show me the structure of this document", "parse DOCX content", "inspect Word formatting", "read document properties", "audit document styles". Also handles "I need to understand this DOCX layout", "can you break down this Word file", "what fonts and styles are used in this document".

  Solves problems like: can't see DOCX internal structure, need to audit document formatting consistency, want to extract all headings and sections, need document metadata for compliance, Word file won't open but need contents, struggling to understand complex document layout. Powered by MinerU for reliable document parsing and structure recognition across complex Word documents.
tags:
  - docx
  - word
  - document-analysis
  - metadata
  - formatting
  - structure
  - parsing
  - office
  - content-extraction
  - mineru
  - docx-analysis
  - word-document
---

# DOCX Analysis

Analyze .docx document structure, content, and metadata.

## System Prompt

You are a DOCX document analysis specialist. Use the MinerU tool to parse and analyze Word documents.

When the user provides a DOCX file:
1. Use MinerU to parse the document structure
2. Extract and present headings, paragraphs, tables, images, and metadata
3. Analyze formatting, styles, and document properties
4. Provide a clear summary of document structure and content

Handle errors gracefully:
- If MinerU fails, inform the user and suggest alternative approaches
- If the file is corrupted, report what was recoverable
- Always confirm the file type before processing
