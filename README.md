# RMarkdown that helps creating academic cover letter

## What is required to make it work?

You  have to be sure that you have **RStudio** and a **TeX editor** (such as MiKTeX or tinytex) installed in your operational system.

## Usage

You will need to have both the `.Rmd` and `.tex` files within the same directory. You can easily do this by cloning or downloading this repository.

The `.tex` file contains the structure or template for this cover letter. If you are satisfied with the structure of the letter, you will not need to edit this file.

You can access and change the sender's, the recipient's and the letter body using the `.Rmd` file. Within the `YMAL` (i.e. the header or *YAML Ain't Markup Language* of the `.Rmd` document), you will find all potential arguments that are accepted within the letter structure.

They are also available here:

```
subject: "Your Letter Subject"
date: "January 24th, 2019"
author: "Pedro Henrique Pereira Braga"
from_email: "ph.pereirabraga@gmail.com"
from_phone: "+1 (514) 123-4567"
from_personal_website: pedrohbraga.github.io
from_institution_logo: yourlogo.jpg
from_position: "Ph.D. Student"
from_professional_title: "M.Sc."
from_institution: "Concordia University"
from_department: "Department of Biology"
from_address: "Your address"
from_city: "Your city"
from_state_province: "State or Province"
from_postalcode: "Your postal code"
from_country: "Canada"
to_professional_title: "Dr."
to_name: "Hermione Granger"
to_department: "Department of Magical Law Enforcement"
to_institution: "Ministry of Magic Headquarters"
to_address: "Whitehall"
to_city: "Westminster"
to_state_province: "London"
to_postal_code: "SW1A 2EU"
to_country: "United Kingdom"
opening_greeting: "Dear Minister for Magic Dr. Granger,"
closing_greeting: "Sincerely,"
```

The arguments `to_department`, `to_institution`, `to_address`, `to_postal_code` and `subject` are optional, and may be removed from the `YAML` at your discretion.

You also have the option of using a logo. Be sure to change the argument  `from_institution_logo`. *Be aware of your institution's policy on the use of logo and related insignia. This is [Concordia University's Policy on the Use of the University's Logo](http://www.concordia.ca/content/dam/common/docs/policies/official-policies/SG-4.pdf?utm_source=redirect&utm_medium=pdf&utm_campaign=SG-4.pdf)* 

## Contributing

If you see any issues or would like to suggest new features and modifications to this template, do not hesitate to communicate with me! The best way is to create an issue in this repository.

Best regards,
Pedro H. P. Braga