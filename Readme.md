## Placebo.js
### Generate fake medical data in the browser and node.js - fork of faker.js
## USAGE
### browser -
      <script src = "Faker.js" type = "text/javascript"></script>
      <script>
        var randomName = Faker.Name.findName(); // Caitlyn Kerluke
        var randomEmail = Faker.Internet.email(); // Rusty@arne.info
        var randomCard = Faker.Helpers.createCard(); // random contact card containing many properties
      </script>
### node.js -
### usage
      var Faker = require('./Faker');
      var randomName = Faker.Name.findName(); // Rowan Nikolaus
      var randomEmail = Faker.Internet.email(); // Kassandra.Haley@erich.biz
      var randomCard = Faker.Helpers.createCard(); // random contact card containing many properties
## API

- Name
    - firstName
    - firstNameMale
    - firstNameFemale
    - lastName
    - findName
    - gender
- Address
    - zipCode
    - zipCodeFormat
    - city
    - streetName
    - streetAddress
    - secondaryAddress
    - brState
    - ukCounty
    - ukCountry
    - usState
    - latitude
    - longitude
- PhoneNumber
    - phoneNumber
    - phoneNumberFormat
- Internet
    - email
    - userName
    - domainName
    - domainWord
    - ip
    - color
- Company
    - suffixes
    - companyName
    - companySuffix
    - catchPhrase
    - bs
- Image
    - avatar
    - imageUrl
    - abstractImage
    - animals
    - business
    - cats
    - city
    - food
    - nightlife
    - fashion
    - people
    - nature
    - sports
    - technics
    - transport
- Lorem
    - words
    - sentence
    - sentences
    - paragraph
    - paragraphs
- Helpers
    - randomNumber
    - randomize
    - slugify
    - replaceSymbolWithNumber
    - shuffle
    - createCard
    - userCard
- Tree
    - clone
    - createTree
- Date
    - past
    - future
    - between
    - recent
- Random
    - number
    - array_element
    - city_prefix
    - city_suffix
    - street_suffix
    - br_state
    - br_state_abbr
    - us_state
    - us_state_abbr
    - uk_country
    - gender
    - first_name
    - first_name_female
    - first_name_male
    - last_name
    - name_prefix
    - name_suffix
    - catch_phrase_adjective
    - catch_phrase_descriptor
    - catch_phrase_noun
    - bs_adjective
    - bs_noun
    - phone_formats
    - domain_suffix
    - avatar_uri
- Definitiions
    - first_name_male
    - first_name_female
    - first_name
    - last_name
    - name_prefix
    - name_suffix
    - br_state
    - br_state_abbr
    - us_state
    - us_state_abbr
    - city_prefix
    - city_suffix
    - street_suffix
    - uk_county
    - uk_country
    - catch_phrase_adjective
    - catch_phrase_descriptor
    - catch_phrase_noun
    - bs_adjective
    - bs_buzz
    - bs_noun
    - domain_suffix
    - lorem
    - phone_formats
    - avatar_uri

## Future API

- Vitals
    - bmi
    - bmi_normal
    - bmi_high
    - bmi_low
    - systolic
    - systolic_normal
    - systolic_high
    - systolic_low
    - diastolic
    - diastolic_normal
    - diastolic_high
    - diastolic_low
    - bp
    - bp_normal
    - bp_high
    - bp_low
    - height
    - weight
    - age
- Allergies
    - allergy
    - allergy_severity
    - allergy_status
- Problems
    - problem
    - problem_rare
    - problem_status
- Procedures
    - procedure
- Vaccines
    - vaccine
    - vaccine_status
- Insurance
    - insurance_company
    - insurance_company_foreign
    - policy_number
    - group_number

## Tests
       npm install .
       make test
You can view a code coverage report generated in coverage/lcov-report/index.html.
## Authors
####Matthew Bergman & Marak Squires
Heavily inspired by Benjamin Curtis's Ruby Gem [Faker](http://faker.rubyforge.org/) and Perl's [Data::Faker](http://search.cpan.org/~jasonk/Data-Faker-0.07/lib/Data/Faker.pm)
<br/>
Copyright (c) 2014 Matthew Bergman & Marak Squires http://github.com/FotoVerite/Faker.js/
<br/>
Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:
<br/>
The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.
<br/>
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
