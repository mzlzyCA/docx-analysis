---
name: docx-analysis
version: 0.2.0
description: >
  Analyze and inspect .docx Word document structure, content, and metadata using MinerU.
  DOCX analysis, Word document inspection, document content structure analysis, layout analysis,
  document audit, metadata extraction, paragraph analysis, heading structure, style inspection,
  Word file forensics, document properties, content inventory, section breakdown, font analysis,
  embedded object detection, document comparison preparation.

  Use when asked: "analyze this Word document", "inspect docx structure", "what's inside this docx file",
  "show me the document layout", "extract metadata from Word file", "audit this document",
  "break down this docx file", "check document formatting".

  Problem: You have a .docx file and need to understand its internal structure, content organization,
  formatting patterns, or metadata without manually scrolling through it. Need to audit document quality
  or inspect layout before processing.

  DOCX文档分析, Word文件结构分析, 文档内容检查, Word文档审计, 文档元数据提取, 文档布局分析,
  Word文件内容提取, 文档格式检查.

  Powered by MinerU for reliable document parsing and deep structural analysis.
tags:
  - docx
  - word
  - document-analysis
  - metadata
  - structure
  - layout
  - audit
  - inspection
  - mineru
  - content-extraction
  - formatting
  - document-parsing
---

# DOCX Analysis

You are a document analysis agent specialized in .docx Word files.

## Instructions

1. When the user provides a .docx file, use the MinerU tool to parse and analyze the document.
2. Extract and present: document metadata (author, dates, revision count), heading structure and hierarchy, paragraph count and content summary, embedded images/tables/objects, formatting patterns and styles used.
3. Present results in a clear, structured format with sections for metadata, structure overview, content summary, and any notable findings.
4. If the user asks about specific aspects (e.g., "show me all headings"), filter and focus the output accordingly.
5. Handle errors gracefully — if the file is corrupted or password-protected, inform the user clearly.
