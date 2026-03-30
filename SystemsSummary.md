# Programme Summary - Functionality, Results, Impact

---

## ET1 & ET2 – Traffic Detection

### What the Code Does
- Captures video using OpenCV  
- Applies background subtraction (**MOG2**) to detect motion  
- Focuses on a defined road region (**ROI**)  
- Uses morphological operations to remove noise  
- Detects objects via contours and draws bounding boxes  

### Results Produced
- Real-time video with detected vehicles highlighted  
- Foreground mask showing motion areas  
- *(Extended)* Vehicle counts and cars-per-minute metrics  

### Impact
- Demonstrates a real-time computer vision pipeline  
- Applicable to:
  - Traffic monitoring systems  
  - Surveillance applications  

---

## E2 – Audio Compression

### What the Code Does
- Reads WAV files and converts audio into numerical arrays  
- Implements **Rice encoding/decoding** from scratch  
- Adds **zlib compression** for comparison  
- Compresses files into `.ex2` format and reconstructs original audio  
- Calculates compression ratios for each method  

### Results Produced
- Compressed audio files (Rice and zlib)  
- Reconstructed WAV files (lossless)  
- Printed comparison of:
  - File sizes  
  - Compression performance  

### Impact
- Shows ability to implement low-level compression algorithms  
- Demonstrates understanding of:
  - Data encoding  
  - Performance evaluation  
- Highlights real-world trade-offs in compression techniques  

---

## ET3 – Video Validation & Conversion

### What the Code Does
- Uses **ffprobe** (via subprocess) to extract video metadata  
- Validates format against predefined requirements  
- Identifies issues:
  - Codec  
  - Resolution  
  - Frame rate  
- *(Extended)* Supports automatic conversion using **ffmpeg**  

### Results Produced
- Structured metadata (**JSON**)  
- List of validation errors for each video  
- Standardized, compliant output videos  

### Impact
- Automates media validation and formatting workflows  
- Demonstrates integration of external tools into Python systems  
- Relevant for:
  - Media platforms  
  - Content processing pipelines
 
