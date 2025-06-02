# NEURAL-STYLE-TRANSFER

##This Neural Style Transfer (NST) project allows users to apply artistic styles to images using deep learning techniques. By leveraging convolutional neural networks (CNN's), the model extracts content and style features from images and blends them together, creating visually compelling artwork.

NST is widely used in creative AI applications, transforming ordinary photographs into stylized masterpieces inspired by famous paintings or unique textures.

##Features

**Custom style application** :Users can blend content images with artistic styles.

**High-resolution output** :Generates images with sharp details.

**Adjustable style strength** :Fine-tune the balance between content and style influence.

**Fast processing** :Optimized implementation using deep learning frameworks.

**Support for multiple styles** :Apply different styles simultaneously.

##Installation

Clone the repository and install dependencies:
```bash
git clone https://github.com/harshiniryali/NEURAL-STYLE-TRANSFER.git
cd NEURAL-STYLE-TRANSFER
pip install -r requirements.txt
```

##Usage

Run the script to stylize an image:
python style_transfer.py --content "content.jpg" --style "style.jpg"

##How it works?

**Feature Extraction** :USes a pre-trained CNN to extract content and style representations.

**Loss calculation** :Cmputes content loss and style loss using gram matrices.

**Optimization process** :Updates a generated image to minimize the loss function.

**Final Output** :Saves and displays the stylized image.

##Contributing

Contributions are welcome! If you'd like to enhance this tool, feel free to fork the repository, submit pull requests, or report issues.

##Output

It is attached to the code below the each shell. Please find the attachment.
