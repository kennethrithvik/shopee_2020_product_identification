# shopee_2020_product_identification
Shopee Code League - Product Detection Detect Real Product On E-commercial Platform


Background
==========

At Shopee, we always strive to ensure the correct listing and categorization of products. For example due to the recent pandemic situation, face masks become extremely popular for both buyers and sellers, everyday we need to categorize and update a huge number of masks items. A robust product detection system will significantly improve the listing and categorization efficiency. But in the industrial field the data is always much more complicated and there exists mis-labelled images, complex background images and low resolution images, etc. The noisy and imbalanced data and multiple categories make this problem still challenging in the modern computer vision field.

#### Note: This page is for participants from open group!

| ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2F8983b696df39ecb3bbd2fb5dcf7303be%2F5d04dd453bbe5b71c00236f9383751e5.jpg?generation=1591669667767485&alt=media) | ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2F56456e8a500366e15d468ccd8d5f13c2%2F3b1519ee1932c8ed960649be4ff35dec.jpg?generation=1591670501765344&alt=media) | ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2F24c4289a420487e7ea3117492a03b29a%2F3d52392446452e4eb7e26e4d762467b3.jpg?generation=1591670956360484&alt=media) |
| ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2Ff4d283fc00b5f2055893fbca2e62a3b3%2F0dbeed1585ee580bf3d9670e8b23ecc8.jpg?generation=1591671179189986&alt=media) | ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2F31f1700efb459542f6d5ad5964f61c39%2F2b346cae0305ece2a7e819b833dfd635.jpg?generation=1591671472191358&alt=media) | ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2F4ca0ca158d7b79f20d3bc2d16abf97e3%2F1cf0391bad6debae1a9cff35153e8962.jpg?generation=1591671513570675&alt=media) |
| ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2F74c7ee5182be4902d42f845f3889a433%2F0ad3826c91d647b659794160adb70f92.jpg?generation=1591672539773817&alt=media) | ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2Fec184aadda0d10cb1b09fa58deb98fc6%2F00ba143008cf454fa24c5f1e1c60c8e5.jpg?generation=1591672611376483&alt=media) | ![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F5198646%2F6cd8f24cdca4b4dc835fcdbe5a9e3cba%2F0d5fae3df34696d2cdc6dc19dfd02057.jpg?generation=1591672648172617&alt=media) |

Task
====

In this competition, a multiple image classification model needs to be built. There are ~100k images within 42 different categories, including essential medical tools like masks, protective suits and thermometers, home & living products like air-conditioner and fashion products like T-shirts, rings, etc. For the data security purpose the category names will be desensitized. The evaluation metrics is top-1 accuracy.
