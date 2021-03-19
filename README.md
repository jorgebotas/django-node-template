# django-node-template
Django template for developing alongside Node.js


1. Fork project
2. Generate secrey key and store at `.env/SECRET_KEY.txt`. Include path in .gitignore
3. Activate environment `source django-node-env/bin/activate`
4. Update pip and install dependencies dependencies

    `pip install --upgrade pip`

    `pip install rcssmin --install-option="--without-c-extensions"`

    `pip install django-compressor django-compressor-toolkit`
    
    `pip install rjsmin --install-option="--without-c-extensions"`

5. Install node dependencies `npm install`
6. Code!
