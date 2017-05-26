To show how hard is to use szero with transpiled code folloe that:

    npm isntall -g szero

    git glone https://github.com/tiagofabre/HowHardIsToUseSZeroWithTranspiledCode.git

    cd HowHardIsToUseSZeroWithTranspiledCode/

    npm install

    npm run build 

    szero ./build

The output is:

    package.json is require
    
    (node:35014) UnhandledPromiseRejectionWarning: Unhandled promise rejection (rejection id: 2): Error: package.json is require
    
    (node:35014) DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.