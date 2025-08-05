# Pipeline Overview

This project turns raw vehicle/towing incident images into **structured tow reports** by chaining four stages:

1) **License Plate OCR** → detects and reads Brazilian license plates from images.  
2) **Vehicle Damage Detection (YOLO)** → finds damaged regions/parts.  
3) **Damage Captioning (BLIP)** → generates natural-language descriptions of the visible damage.  
4) **Report Generation** → merges plates, detections and captions into a final PDF/JSON report.

> The reference training and prototype code for each stage comes from the Kaggle notebooks:
> - OCR API: *OCR_Plate_API*  
> - Captioning: *BLIP_FineTune*  
> - Detection: *YOLO_FineTune_CarDD*  
> - Reporting: *Report_Generator*



