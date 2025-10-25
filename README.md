# 📊 PDF to PowerPoint Reconstructor using DeepSeek-OCR

> **⚠️ Proof of Concept**: This project is currently in the idea/prototype stage and requires further development for production use.

Convert PDF slide decks back into editable PowerPoint presentations using AI-powered OCR with spatial layout preservation.

## 🎯 What Does This Do?

This tool takes a **PDF of presentation slides** and reconstructs them into an **editable PowerPoint (.pptx)** file by:

1. **Extracting** text, images, and tables with precise bounding boxes using DeepSeek-OCR
2. **Preserving** the exact layout and positioning of all elements
3. **Rendering** markdown formatting (bold, italic, headers)
4. **Reconstructing** tables in native PowerPoint format
5. **Positioning** all elements exactly where they appeared in the original slides

## ✨ Features

- 🔍 **AI-Powered OCR**: Uses DeepSeek-OCR for accurate text extraction with spatial awareness
- 📐 **Layout Preservation**: Maintains exact positioning of all elements (text, images, tables)
- 📊 **Table Recognition**: Converts markdown tables to native PowerPoint tables
- 🎨 **Formatting Support**: Preserves titles, subtitles, and text formatting
- 🖼️ **Image Extraction**: Extracts and places images in their original positions
- 📄 **Batch Processing**: Processes multi-page PDFs automatically

## 🚧 Current Status: Prototype

This is a **proof of concept** demonstrating the feasibility of AI-based slide reconstruction. 

### Known Limitations:
- ⚠️ Requires manual environment setup (Google Colab recommended)
- ⚠️ Memory intensive (needs GPU with 8GB+ VRAM)
- ⚠️ Layout precision depends on OCR accuracy
- ⚠️ Complex layouts may need manual adjustment
- ⚠️ Limited to basic markdown formatting
- ⚠️ Table detection could be improved
- ⚠️ No font matching from original slides

### TODO for Production:
- [ ] Standalone script (non-Colab)
- [ ] Error handling improvements
- [ ] Font style matching
- [ ] Better table detection
- [ ] Color scheme preservation
- [ ] Animation support
- [ ] CLI interface
- [ ] Docker containerization
- [ ] Batch processing optimization
- [ ] Web interface

