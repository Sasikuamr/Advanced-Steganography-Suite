# 🔐 Advanced Steganography Suite

**Winner-Ready Hackathon Project** - Military-grade secret message hiding in images

## 🚀 Unique Features That Set Us Apart

### 🎯 **Multiple Encoding Algorithms**
- **LSB (Least Significant Bit)** - Classic but optimized
- **DCT (Discrete Cosine Transform)** - JPEG-resistant encoding
- **PVD (Pixel Value Differencing)** - Adaptive capacity based on image complexity

### 🔒 **Military-Grade Security**
- **Fernet Encryption** - Symmetric encryption with password protection
- **SHA-256 Key Derivation** - Secure password-to-key conversion
- **Metadata Embedding** - Timestamp and method information
- **Message Compression** - Optional ZIP compression for larger messages

### 🎨 **Advanced UI/UX**
- **Real-time Analysis** - Entropy calculation and LSB visualization
- **Interactive Dashboard** - Multiple modes with smooth transitions
- **Progress Indicators** - Real-time encoding/decoding feedback
- **Statistics Display** - File size changes and capacity analysis

### 🔍 **Forensic Analysis Tools**
- **LSB Plane Visualization** - See hidden data patterns
- **Entropy Analysis** - Detect presence of hidden information
- **Capacity Calculator** - Maximum message size estimation
- **Randomness Scoring** - Statistical analysis of image data

## 🏆 What Makes This Hackathon-Winning

1. **Technical Sophistication**: Multiple algorithms, not just basic LSB
2. **Security Focus**: Real encryption, not just obfuscation
3. **User Experience**: Professional UI with analysis tools
4. **Practical Application**: Real-world forensic capabilities
5. **Scalability**: Handles large messages with compression
6. **Innovation**: Adaptive encoding based on image characteristics

## 🚀 Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py

# Generate demo images (optional)
python demo.py
```

## 💡 Usage Examples

### Hide a Message
1. Upload any image (PNG, JPG, BMP)
2. Enter your secret message
3. Set a strong password
4. Choose encoding method
5. Download the encoded image

### Extract a Message
1. Upload the encoded image
2. Enter the correct password
3. Select the same encoding method
4. View the extracted message and metadata

### Analyze an Image
1. Upload any image for analysis
2. View LSB planes and entropy statistics
3. Detect potential hidden data

## 🎯 Hackathon Judging Criteria Coverage

- **Innovation**: Multiple encoding algorithms + forensic analysis
- **Technical Complexity**: Encryption, compression, multiple methods
- **User Experience**: Professional Streamlit interface
- **Practical Value**: Real-world steganography applications
- **Code Quality**: Clean, documented, modular design
- **Demonstration**: Built-in demo generator and analysis tools

## 🔧 Technical Architecture

```
app.py                 # Main Streamlit application
├── AdvancedSteganography  # Core steganography class
│   ├── LSB encoding       # Least Significant Bit
│   ├── DCT encoding       # Discrete Cosine Transform
│   ├── PVD encoding       # Pixel Value Differencing
│   └── Encryption layer   # Fernet + SHA-256
├── UI Components          # Streamlit interface
│   ├── Hide Message       # Encoding interface
│   ├── Extract Message    # Decoding interface
│   └── Analysis Tools     # Forensic analysis
└── Demo Generator         # Sample image creation
```

## 🎨 Screenshots & Demo

The application features:
- **Gradient headers** with professional styling
- **Real-time statistics** showing file size changes
- **Visual LSB analysis** revealing hidden data patterns
- **Interactive controls** for all encoding parameters
- **Download functionality** for encoded images
- **Metadata display** with encoding information

## 🏅 Competitive Advantages

1. **Multiple Algorithms**: Not just LSB - includes DCT and PVD
2. **Real Encryption**: Uses Fernet, not simple XOR
3. **Forensic Tools**: Can analyze and detect steganography
4. **Professional UI**: Streamlit with custom CSS styling
5. **Compression Support**: Handles large messages efficiently
6. **Metadata Tracking**: Embeds encoding information
7. **Quality Control**: Adjustable output quality settings
8. **Cross-format Support**: Works with PNG, JPG, BMP

## 🎯 Perfect for Hackathon Presentation

- **Live Demo Ready**: Upload, encode, decode in real-time
- **Visual Impact**: LSB visualization shows hidden data
- **Technical Depth**: Multiple algorithms demonstrate expertise
- **Practical Application**: Real-world cybersecurity relevance
- **User-Friendly**: Judges can try it themselves easily

## 🔮 Future Enhancements

- Audio steganography support
- Blockchain-based message verification
- AI-powered steganalysis detection
- Mobile app version
- Batch processing capabilities

---

**Built for Excellence** | **Ready to Win** | **Steganography Redefined**