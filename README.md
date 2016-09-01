This repository contains notes I took when using diverse tools and reading IT-related articles, over the last 10 years.

It should give a good idea of what I can work with, although it is primarly intended for my own usage.
This covers:
  - _[Languages](Architecture/Languages)_: [JavaScript](Architecture/Languages/JavaScript/JavaScript.language.txt) (including [ES6](Architecture/Languages/JavaScript/JavaScript.language.txt), [Node](Architecture/Networking/RPC/HTTP/Server/Framework/nodejs.javascript.txt), [DOM](Architecture/Languages/JavaScript/DOM/DOM.javascript.txt), [Web APIs](Architecture/Languages/JavaScript/DOM/DOM.javascript.txt)), [HTML](Architecture/Languages/HTML/HTML.language.txt), [CSS](Architecture/Languages/CSS/CSS.language.txt), [Bash](To_sort/Bash_Unix/Bash/bash.txt), [SQL](Architecture/State/Database/Relational/SQL/SQL.database.txt), [C](Architecture/Languages/C_C++/C.language.txt), [C++](Architecture/Languages/C_C++/C++.language.txt), [ASM x86](Architecture/Languages/x86), [R](Architecture/Languages/R.language.txt), [VBA](Architecture/Languages/VBA)
     - _Transcompiled languages_: [CoffeeScript](Architecture/Languages/JavaScript/Transcompilation/coffeescript.language.txt), [Jade/Pug](Architecture/Languages/HTML/Transcompilation/jade.language.txt), [Sass](Architecture/Languages/CSS/Transcompilation/_sass.language.txt), [Less](Architecture/Languages/CSS/Transcompilation/_less.language.txt), [PostCSS](Architecture/Languages/CSS/Transcompilation/postcss.language.txt)
  - _[Theory](Theory)_: [design patterns](Theory), [algorithms](Theory/Algorithms), [type theory](Theory/Types)
  - _Procotols_: [HTTP](Architecture/Networking/RPC/HTTP/HTTP.protocol.txt) (including [REST](Architecture/Networking/RPC/HTTP)), [WebSocket](Functional_requirements/Realtime/WebSocket), [TCP](Architecture/Networking/Routing/TCP.protocol.txt)
  - _Frameworks_: [Node](Architecture/Networking/RPC/HTTP/Server/Framework/nodejs.javascript.txt) (including [Express](Architecture/Networking/RPC/HTTP/Server/Framework/express.node.txt), [Sails](Architecture/Networking/RPC/HTTP/Server/Framework/sails.express.txt)), [React](Non_functional_requirements/Maintainability/Operability/Abstraction/MVC/Frameworks/View/React/react.javascript.txt), [Flux](Non_functional_requirements/Maintainability/Operability/Abstraction/MVC/Frameworks/State/Flux/flux.javascript.txt)/[Redux](Non_functional_requirements/Maintainability/Operability/Abstraction/MVC/Frameworks/State/Flux/Redux/redux.flux.txt), [Angular](Non_functional_requirements/Maintainability/Operability/Abstraction/MVC/Frameworks/Full/angular.javascript.txt), [Backbone](Non_functional_requirements/Maintainability/Operability/Abstraction/MVC/Frameworks/Full/Backbone/backbone_marionette.javascript.txt) (including [Marionette](Non_functional_requirements/Maintainability/Operability/Abstraction/MVC/Frameworks/Full/Backbone/backbone_marionette.javascript.txt))
  - _[Databases](Architecture/State/Database)_: [PostgreSQL](Architecture/State/Database/Relational/SQL/SQL.database.txt), [MongoDB](Architecture/State/Database/Document_oriented/mongodb.database.txt), [Redis](Architecture/State/Database/Key_value/redis.database.txt)
  - _[Platforms](Architecture/Platform)_: [mobile](Architecture/Platform/Mobile), [Chrome extensions](Architecture/Platform/Browser/Extensions/Chrome_extensions_apps.javascript.txt)
  - _[Cloud](Architecture/Platform/Cloud)_: [AWS](Architecture/Platform/Cloud/IaaS/AWS.saas.txt)
  - _[Testing](Non_functional_requirements/Quality/Stability/Testing)_: [unit](Non_functional_requirements/Quality/Stability/Testing/Unit_tests) ([Mocha](Non_functional_requirements/Quality/Stability/Testing/Test_runners/Unit_test_runner/mocha.node_cli.txt), [Jasmine](Non_functional_requirements/Quality/Stability/Testing/Test_runners/Unit_test_runner/_jasmine.node_cli.txt), [QUnit](Non_functional_requirements/Quality/Stability/Testing/Test_runners/Unit_test_runner/_qunit.cli.txt), [Karma](Non_functional_requirements/Quality/Stability/Testing/Test_runners/Full_runner/karma.cli.txt)), [browser](Non_functional_requirements/Quality/Stability/Testing/Browser_testing) ([Selenium](Non_functional_requirements/Quality/Stability/Testing/Browser_testing/Selenium)), [CSS](Non_functional_requirements/Quality/Stability/Testing/CSS), [performance](Non_functional_requirements/Quality/Stability/Testing/Performance), [stress](Non_functional_requirements/Quality/Stability/Testing/Stress)
  - _[User experience](Non_functional_requirements/User_experience)_: [usability](Non_functional_requirements/User_experience/Usability), [design](Non_functional_requirements/User_experience/Design), [internationalization](Non_functional_requirements/User_experience/Internationalization), [accessibility](Non_functional_requirements/User_experience/Accessibility/accessibility.theory.txt)
  - _[Performance](Non_functional_requirements/User_experience/Performance)_: [async](Non_functional_requirements/User_experience/Performance/Async), [caching](Non_functional_requirements/User_experience/Performance/Computation_reduction/Caching), [lazy loading](Non_functional_requirements/User_experience/Performance/Computation_reduction/Lazy_loading), [concurrency](Non_functional_requirements/User_experience/Performance/Concurrency), [compression](Non_functional_requirements/User_experience/Performance/Space_reduction/Compression), [minification](Non_functional_requirements/User_experience/Performance/Space_reduction/Minification)
  - _[Quality](Non_functional_requirements/Quality)_: [monitoring](Non_functional_requirements/Quality/Monitoring), [security](Non_functional_requirements/Quality/Stability/Security), [validation](Non_functional_requirements/Quality/Stability/Validation), [high availability](Non_functional_requirements/Quality/Stability/Availability), [debugging](Non_functional_requirements/Quality/Vulnerability/Debugging)
  - _[Ease to maintain](Non_functional_requirements/Maintainability)_: [functional programming](Non_functional_requirements/Maintainability/Operability/Abstraction/Functional), [static analysis](Non_functional_requirements/Maintainability/Operability/Static_analysis), [documenting](Non_functional_requirements/User_experience/Usability/Documenting)
  - _[Automating](Non_functional_requirements/Maintainability/Operability/Automation)_: [build automation](Non_functional_requirements/Maintainability/Operability/Automation/Build_automation), [continuous integration](Non_functional_requirements/Maintainability/Operability/Automation/Continuous_integration)
  - _Others_: [analytics](Functional_requirements/Analytics), [realtime](Functional_requirements/Realtime)

# Size #

Number of files: 823  
Number of lines: 160616  
Number of pages (if it were a printed book): 6424  

# List of files #

## Architecture ##

### Async ###

- __Concurrency__
  - [concurring programming (Theory)](Architecture/Async/Concurrency/concurring_programming.theory.txt)
- __Control flow__
  - [async (JavaScript)](Architecture/Async/Control_flow/async.javascript.txt)
- __Events__
  - [propagate (Node)](Architecture/Async/Events/propagate.node.txt)
  - [eventemitter2 (JavaScript)](Architecture/Async/Events/eventemitter2.javascript.txt)
- __Parallelism__
  - [parallellism (Theory)](Architecture/Async/Parallelism/parallellism.theory.txt)
- __Promises__
  - [q (JavaScript)](Architecture/Async/Promises/_q.javascript.txt)
  - [bluebird (JavaScript)](Architecture/Async/Promises/bluebird.javascript.txt)
  - [redux-promise-middleware (Redux)](Architecture/Async/Promises/redux-promise-middleware.redux.txt)
- __Signals__
  - [signal handler (C)](Architecture/Async/Signals/signal_handler.c.txt)
- __Streams__
  - [event-stream (Node)](Architecture/Async/Streams/event-stream.node.txt)
  - [through (Node)](Architecture/Async/Streams/through.node.txt)

### Code design ###

- __Algorithms__
  - [data structures (Theory)](Architecture/Code_design/Algorithms/data_structures.theory.txt)
  - [time complexity (Theory)](Architecture/Code_design/Algorithms/time_complexity.theory.txt)
  - [turing machine (Theory)](Architecture/Code_design/Algorithms/turing_machine.theory.txt)
- __Design patterns__
  - [design patterns (Theory)](Architecture/Code_design/Design_patterns/design_patterns.theory.txt)
  - [software rot (Theory)](Architecture/Code_design/Design_patterns/software_rot.theory.txt)
- __Information theory__
  - [information theory (Theory)](Architecture/Code_design/Information_theory/information_theory.theory.txt)
- __Requirements__
  - [abstraction (Theory)](Architecture/Code_design/Requirements/abstraction.theory.txt)
  - [extensibility (Theory)](Architecture/Code_design/Requirements/extensibility.theory.txt)
  - [flexibility (Theory)](Architecture/Code_design/Requirements/flexibility.theory.txt)
  - [interactivity (Theory)](Architecture/Code_design/Requirements/interactivity.theory.txt)
  - [interchangeability (Theory)](Architecture/Code_design/Requirements/interchangeability.theory.txt)
  - [maintainability (Theory)](Architecture/Code_design/Requirements/maintainability.theory.txt)
  - [modularity (Theory)](Architecture/Code_design/Requirements/modularity.theory.txt)
  - [requirements (Theory)](Architecture/Code_design/Requirements/requirements.theory.txt)
  - [reusability (Theory)](Architecture/Code_design/Requirements/reusability.theory.txt)
  - [stability (Theory)](Architecture/Code_design/Requirements/stability.theory.txt)
- __Software methodology__
  - [domain driven design (Theory)](Architecture/Code_design/Software_methodology/domain_driven_design.theory.txt)
  - [general programming (Theory)](Architecture/Code_design/Software_methodology/general_programming.theory.txt)
- __Types__
  - [functions (Theory)](Architecture/Code_design/Types/functions.theory.txt)
  - [object oriented (Theory)](Architecture/Code_design/Types/object_oriented.theory.txt)
  - [polymorphism (Theory)](Architecture/Code_design/Types/polymorphism.theory.txt)
  - [types (Theory)](Architecture/Code_design/Types/types.theory.txt)

### Dependencies ###

- __Compatibility__
  - __Versioning__
    - __Changelog__
      - __Generation__
        - [headway (SaaS)](Architecture/Dependencies/Compatibility/Versioning/Changelog/Generation/headway.saas.txt)
        - [conventional changelog (Node)](Architecture/Dependencies/Compatibility/Versioning/Changelog/Generation/conventional_changelog.node.txt)
      - [changelog (Theory)](Architecture/Dependencies/Compatibility/Versioning/Changelog/changelog.theory.txt)
    - [versioning (Theory)](Architecture/Dependencies/Compatibility/Versioning/versioning.theory.txt)
  - [compatibility (Theory)](Architecture/Dependencies/Compatibility/compatibility.theory.txt)
  - [standards list (Theory)](Architecture/Dependencies/Compatibility/standards_list.theory.txt)
- __Dependency deprecation security__
  - __Deprecation security__
    - [gemnasium (SaaS)](Architecture/Dependencies/Dependency_deprecation_security/Deprecation_security/gemnasium.saas.txt)
- __Dependency loaders__
  - [UMD (JavaScript)](Architecture/Dependencies/Dependency_loaders/UMD.javascript.txt)
  - [browserify (Node CLI)](Architecture/Dependencies/Dependency_loaders/browserify.node_cli.txt)
  - [loader comparison (Summary)](Architecture/Dependencies/Dependency_loaders/loader_comparison.summary.txt)
  - [requirejs (JavaScript)](Architecture/Dependencies/Dependency_loaders/requirejs.javascript.txt)
  - [systemjs (Node CLI)](Architecture/Dependencies/Dependency_loaders/systemjs.node_cli.txt)
- __Dependency manager__
  - __Client__
    - [bower (Node CLI)](Architecture/Dependencies/Dependency_manager/Client/bower.node_cli.txt)
    - [npm (Node CLI)](Architecture/Dependencies/Dependency_manager/Client/npm.node_cli.txt)
- __Packaging__
  - __OS packages__
    - [deb packaging (Theory)](Architecture/Dependencies/Packaging/OS_packages/deb_packaging.theory.txt)
- __Runtime manager__
  - [nvm (Node)](Architecture/Dependencies/Runtime_manager/nvm.node.txt)

### Functional ###

- __Immutable__
  - [immutable (JavaScript)](Architecture/Functional/Immutable/immutable.javascript.txt)
- __Utilities__
  - [clone_deep equal deep merge (Node)](Architecture/Functional/Utilities/clone_deep_equal_deep_merge.node.txt)
  - [recompose (React)](Architecture/Functional/Utilities/recompose.react.txt)
  - [reselect (Node)](Architecture/Functional/Utilities/reselect.node.txt)
  - [underscore lodash immutable (JavaScript)](Architecture/Functional/Utilities/underscore_lodash_immutable.javascript.txt)

### Performance ###

- __Compression__
  - __Gzip__
    - [gulp-gzip (Gulp)](Architecture/Performance/Compression/Gzip/gulp-gzip.gulp.txt)
  - __HTTP__
    - [compression (Express)](Architecture/Performance/Compression/HTTP/compression.express.txt)
    - [vary (Node)](Architecture/Performance/Compression/HTTP/vary.node.txt)
  - __Tar__
    - [gulp-tar (Gulp)](Architecture/Performance/Compression/Tar/gulp-tar.gulp.txt)
  - [compression (Theory)](Architecture/Performance/Compression/compression.theory.txt)
  - [compression algos (Theory)](Architecture/Performance/Compression/compression_algos.theory.txt)
  - __zpaq__
    - [libzpaq (C++)](Architecture/Performance/Compression/zpaq/libzpaq.c++.txt)
- __Memory management__
  - [garbage collection (Theory)](Architecture/Performance/Memory_management/garbage_collection.theory.txt)
  - [memory management (Theory)](Architecture/Performance/Memory_management/memory_management.theory.txt)
  - [virtual memory (Theory)](Architecture/Performance/Memory_management/virtual_memory.theory.txt)
- __Optimization__
  - __Lazy loading__
    - __Infinite scrolling__
      - [nginfinitescroll (Angular)](Architecture/Performance/Optimization/Lazy_loading/Infinite_scrolling/nginfinitescroll.angular.txt)
    - __HTML images__
      - [jquery.lazyload (jQuery)](Architecture/Performance/Optimization/Lazy_loading/HTML_images/jquery.lazyload.jquery.txt)
    - __Pagination__
      - [express-paginate (Express)](Architecture/Performance/Optimization/Lazy_loading/Pagination/express-paginate.express.txt)
      - [jquery-bootstrap-pagination (Bootstrap)](Architecture/Performance/Optimization/Lazy_loading/Pagination/jquery-bootstrap-pagination.bootstrap.txt)
  - __Caching__
    - __HTTP__
      - __Conditional__
        - [etag (Node)](Architecture/Performance/Optimization/Caching/HTTP/Conditional/etag.node.txt)
        - [fresh (Node)](Architecture/Performance/Optimization/Caching/HTTP/Conditional/fresh.node.txt)
      - __Unconditional__
        - [versionator (Express)](Architecture/Performance/Optimization/Caching/HTTP/Unconditional/versionator.express.txt)
    - __LRU__
      - [lru-cache (Node)](Architecture/Performance/Optimization/Caching/LRU/lru-cache.node.txt)
  - __Pooling__
    - [generic-pool (Node)](Architecture/Performance/Optimization/Pooling/generic-pool.node.txt)
  - __Timeout__
    - [connect-timeout (Express)](Architecture/Performance/Optimization/Timeout/connect-timeout.express.txt)
    - [toobusy (Node)](Architecture/Performance/Optimization/Timeout/toobusy.node.txt)
- __Performance analytics__
  - __Client side__
    - [phantomas (Node CLI)](Architecture/Performance/Performance_analytics/Client_side/phantomas.node_cli.txt)
    - [response-time (Express)](Architecture/Performance/Performance_analytics/Client_side/response-time.express.txt)
- __Performance testing__
  - __Load testing__
    - [tsung (CLI)](Architecture/Performance/Performance_testing/Load_testing/tsung.cli.txt)
- [performance (Theory)](Architecture/Performance/performance.theory.txt)

### Security ###

- __Authentication__
  - __Common websites__
    - [cognito (AWS)](Architecture/Security/Authentication/Common_websites/cognito.aws.txt)
  - __Framework__
    - [passport (Express)](Architecture/Security/Authentication/Framework/passport.express.txt)
  - __HTTP__
    - [web authentication (HTTP)](Architecture/Security/Authentication/HTTP/web_authentication.http.txt)
  - __JWT__
    - [jws (Node)](Architecture/Security/Authentication/JWT/jws.node.txt)
    - [jwt (Format)](Architecture/Security/Authentication/JWT/jwt.format.txt)
- __Authorization__
  - __Framework__
    - [connect-roles (Express)](Architecture/Security/Authorization/Framework/connect-roles.express.txt)
    - [IAM STS (AWS)](Architecture/Security/Authorization/Framework/IAM_STS.aws.txt)
  - __OAuth__
    - __Server__
      - [oauth2orize (Node)](Architecture/Security/Authorization/OAuth/Server/oauth2orize.node.txt)
      - [passport-oauth2 (Express)](Architecture/Security/Authorization/OAuth/Server/passport-oauth2.express.txt)
    - [oauth (Protocol)](Architecture/Security/Authorization/OAuth/oauth.protocol.txt)
    - __Client__
      - [oauth (JavaScript)](Architecture/Security/Authorization/OAuth/Client/oauth.javascript.txt)
- __Cryptography__
  - __Algorithm__
    - __General__
      - __Hash__
        - [pwd (Node)](Architecture/Security/Cryptography/Algorithm/General/Hash/pwd.node.txt)
        - [hash function (Theory)](Architecture/Security/Cryptography/Algorithm/General/Hash/hash_function.theory.txt)
      - [mac digital signature (Theory)](Architecture/Security/Cryptography/Algorithm/General/mac_digital_signature.theory.txt)
      - [stream ciphers (Theory)](Architecture/Security/Cryptography/Algorithm/General/stream_ciphers.theory.txt)
      - [block ciphers (Theory)](Architecture/Security/Cryptography/Algorithm/General/block_ciphers.theory.txt)
      - [crypto padding (Theory)](Architecture/Security/Cryptography/Algorithm/General/crypto_padding.theory.txt)
    - __Specific__
      - [algo mac (Theory)](Architecture/Security/Cryptography/Algorithm/Specific/algo_mac.theory.txt)
      - [algos classiques (Theory)](Architecture/Security/Cryptography/Algorithm/Specific/algos_classiques.theory.txt)
  - __Certifications__
    - [certifications (Theory)](Architecture/Security/Cryptography/Certifications/certifications.theory.txt)
  - __Checksum__
    - [luhn (Format)](Architecture/Security/Cryptography/Checksum/luhn.format.txt)
  - __Cryptanalyse__
    - __Brute force__
      - [express-brute (Express)](Architecture/Security/Cryptography/Cryptanalyse/Brute_force/express-brute.express.txt)
    - [crypta attacks (Theory)](Architecture/Security/Cryptography/Cryptanalyse/crypta_attacks.theory.txt)
    - [cryptanalyse (Theory)](Architecture/Security/Cryptography/Cryptanalyse/cryptanalyse.theory.txt)
    - [crypta classique attacks (Theory)](Architecture/Security/Cryptography/Cryptanalyse/crypta_classique_attacks.theory.txt)
  - __Email__
    - [openPGP (GUI)](Architecture/Security/Cryptography/Email/openPGP.gui.txt)
  - __History__
    - [histoire crypto (Theory)](Architecture/Security/Cryptography/History/histoire_crypto.theory.txt)
  - __Key__
    - [keygrip (Node)](Architecture/Security/Cryptography/Key/keygrip.node.txt)
    - [crypto key (Format)](Architecture/Security/Cryptography/Key/crypto_key.format.txt)
  - __Legal__
    - [crypto laws (Theory)](Architecture/Security/Cryptography/Legal/crypto_laws.theory.txt)
  - __Theory__
    - [asymetric crypto (Theory)](Architecture/Security/Cryptography/Theory/asymetric_crypto.theory.txt)
    - [authentication (Theory)](Architecture/Security/Cryptography/Theory/authentication.theory.txt)
    - [crypto general (Theory)](Architecture/Security/Cryptography/Theory/crypto_general.theory.txt)
    - [crypto goals (Theory)](Architecture/Security/Cryptography/Theory/crypto_goals.theory.txt)
    - [crypto hardware (Theory)](Architecture/Security/Cryptography/Theory/crypto_hardware.theory.txt)
    - [crypto systems (Theory)](Architecture/Security/Cryptography/Theory/crypto_systems.theory.txt)
    - [random (Theory)](Architecture/Security/Cryptography/Theory/random.theory.txt)
    - [information security (Theory)](Architecture/Security/Cryptography/Theory/information_security.theory.txt)
- __Security general__
  - __Sanitization__
    - [sprintf.js (JavaScript)](Architecture/Security/Security_general/Sanitization/sprintf.js.javascript.txt)
  - __Web__
    - [Web security (Theory)](Architecture/Security/Security_general/Web/Web_security.theory.txt)
    - [cors (Express)](Architecture/Security/Security_general/Web/cors.express.txt)
    - [helmet (Express)](Architecture/Security/Security_general/Web/helmet.express.txt)
    - [csurf (Express)](Architecture/Security/Security_general/Web/csurf.express.txt)
- __Steganography__
  - [steganography (Theory)](Architecture/Security/Steganography/steganography.theory.txt)
  - [stego logiciels (CLI GUI)](Architecture/Security/Steganography/stego_logiciels.cli_gui.txt)

## Data ##

### Distributed filesystem ###

- __Protocols__
  - [FTP (Protocol)](Data/Distributed_filesystem/Protocols/FTP.protocol.txt)

### Files ###

- __Files general__
  - __Commands__
    - __Listing__
      - [glob-stream (Node)](Data/Files/Files_general/Commands/Listing/glob-stream.node.txt)
      - [glob (Node)](Data/Files/Files_general/Commands/Listing/glob.node.txt)
    - __Watchers__
      - [gaze (Node)](Data/Files/Files_general/Commands/Watchers/gaze.node.txt)
  - __Filesystem abstraction__
    - [vinyl (Node)](Data/Files/Files_general/Filesystem_abstraction/vinyl.node.txt)
  - [file uri scheme (Identifier)](Data/Files/Files_general/file_uri_scheme.identifier.txt)

### Markup ###

- __HTML__
  - [HTML (Language)](Data/Markup/HTML/HTML.language.txt)
  - __Transpiler__
    - [jade (Language)](Data/Markup/HTML/Transpiler/jade.language.txt)
- __Markdown__
  - __Syntax__
    - [markdown (Language)](Data/Markup/Markdown/Syntax/markdown.language.txt)
- __Templates__
  - __HTML__
    - [classnames (JavaScript)](Data/Markup/Templates/HTML/classnames.javascript.txt)
  - __Strings__
    - [consolidate (Node)](Data/Markup/Templates/Strings/consolidate.node.txt)
    - [mustache hogan handlebars (Node CLI)](Data/Markup/Templates/Strings/mustache_hogan_handlebars.node_cli.txt)

### Serialization ###

- __CSV__
  - __Syntax__
    - [csv (Node)](Data/Serialization/CSV/Syntax/csv.node.txt)
    - [dsv tsv csv (Format)](Data/Serialization/CSV/Syntax/dsv_tsv_csv.format.txt)
- __Excel__
  - __Parsing serializing__
    - [xlsx (JavaScript)](Data/Serialization/Excel/Parsing_serializing/xlsx.javascript.txt)
- __XML__
  - __Syntax__
    - [XML (Format)](Data/Serialization/XML/Syntax/XML.format.txt)
- __JSON__
  - __Syntax__
    - [cson (Node CLI)](Data/Serialization/JSON/Syntax/cson.node_cli.txt)
    - [json (Format)](Data/Serialization/JSON/Syntax/json.format.txt)
    - [eson (Node)](Data/Serialization/JSON/Syntax/eson.node.txt)

### State ###

- __Client server state__
  - __Cookies__
    - __Integrity__
      - [cookie-signature (Node)](Data/State/Client_server_state/Cookies/Integrity/cookie-signature.node.txt)
    - __Parsing__
      - [cookie (Node)](Data/State/Client_server_state/Cookies/Parsing/_cookie.node.txt)
      - [cookie-parser (Express)](Data/State/Client_server_state/Cookies/Parsing/cookie-parser.express.txt)
      - [jquery-cookie (jQuery)](Data/State/Client_server_state/Cookies/Parsing/_jquery-cookie.jquery.txt)
      - [js-cookie (JavaScript)](Data/State/Client_server_state/Cookies/Parsing/js-cookie.javascript.txt)
    - __Session__
      - [express-session (Express)](Data/State/Client_server_state/Cookies/Session/express-session.express.txt)
  - __General__
    - [connect-flash (Express)](Data/State/Client_server_state/General/connect-flash.express.txt)
    - [express-state (Express)](Data/State/Client_server_state/General/express-state.express.txt)
- __Databases__
  - __Client only__
    - [localforage (JavaScript)](Data/State/Databases/Client_only/localforage.javascript.txt)
  - __Document oriented__
    - [mongodb (Database)](Data/State/Databases/Document_oriented/mongodb.database.txt)
  - __ORM__
    - __Many types__
      - [waterline (Node)](Data/State/Databases/ORM/Many_types/waterline.node.txt)
  - __Key value__
    - __Structured__
      - [elasticache (Database)](Data/State/Databases/Key_value/Structured/elasticache.database.txt)
      - [redis (Database)](Data/State/Databases/Key_value/Structured/redis.database.txt)
  - __Relational__
    - [SQL (Database)](Data/State/Databases/Relational/SQL.database.txt)
    - [rds (AWS)](Data/State/Databases/Relational/rds.aws.txt)
  - __Relations__
    - [normalizr (JavaScript)](Data/State/Databases/Relations/normalizr.javascript.txt)
    - [backbone-relational (Backbone)](Data/State/Databases/Relations/backbone-relational.backbone.txt)
  - [database theory (Theory)](Data/State/Databases/database_theory.theory.txt)
- __Identifiers__
  - __Full-content__
    - [data uri (Identifier)](Data/State/Identifiers/Full-content/data_uri.identifier.txt)
  - __Hash__
    - [ni (Identifier)](Data/State/Identifiers/Hash/ni.identifier.txt)
    - [sigmund (Node)](Data/State/Identifiers/Hash/sigmund.node.txt)
  - __Human-friendly__
    - [nih (Identifier)](Data/State/Identifiers/Human-friendly/nih.identifier.txt)
    - [tag (Identifier)](Data/State/Identifiers/Human-friendly/tag.identifier.txt)
  - __Others__
    - [publicid fpi (Identifier)](Data/State/Identifiers/Others/publicid_fpi.identifier.txt)
    - [oid (Identifier)](Data/State/Identifiers/Others/oid.identifier.txt)
    - [doi (Identifier)](Data/State/Identifiers/Others/doi.identifier.txt)
    - [urn (Identifier)](Data/State/Identifiers/Others/urn.identifier.txt)
  - __URI__
    - __Manipulation__
      - __Query string__
        - [qs (Node)](Data/State/Identifiers/URI/Manipulation/Query_string/qs.node.txt)
      - [uri.js (JavaScript)](Data/State/Identifiers/URI/Manipulation/uri.js.javascript.txt)
    - __Templates__
      - [uri-templates (JavaScript)](Data/State/Identifiers/URI/Templates/uri-templates.javascript.txt)
    - [URI (Identifier)](Data/State/Identifiers/URI/URI.identifier.txt)
  - [identifiers (Summary)](Data/State/Identifiers/identifiers.summary.txt)
  - [web architecture (Theory)](Data/State/Identifiers/web_architecture.theory.txt)
  - __Decentralized__
    - __UUID__
      - [uuid (Identifier)](Data/State/Identifiers/Decentralized/UUID/uuid.identifier.txt)
      - [node-uuid (Node)](Data/State/Identifiers/Decentralized/UUID/node-uuid.node.txt)
- __Validation__
  - __DOM binding__
    - __JavaScript__
      - [backbone-validation (Backbone)](Data/State/Validation/DOM_binding/JavaScript/backbone-validation.backbone.txt)
      - [redux-form (Redux)](Data/State/Validation/DOM_binding/JavaScript/redux-form.redux.txt)
  - __General__
    - [validator.js (JavaScript)](Data/State/Validation/General/validator.js.javascript.txt)
    - [joi (Node)](Data/State/Validation/General/joi.node.txt)
  - [validation (Theory)](Data/State/Validation/validation.theory.txt)
- [state (Theory)](Data/State/state.theory.txt)

## Data science ##

### Computation ###

- __Math__
  - [algebre (Theory)](Data_science/Computation/Math/algebre.theory.txt)
  - [calculus (Theory)](Data_science/Computation/Math/calculus.theory.txt)
  - [combinatoire (Theory)](Data_science/Computation/Math/combinatoire.theory.txt)
  - [equations polynomes (Theory)](Data_science/Computation/Math/equations_polynomes.theory.txt)
  - [financial math (Theory)](Data_science/Computation/Math/financial_math.theory.txt)
  - [fonctions (Theory)](Data_science/Computation/Math/fonctions.theory.txt)
  - [game theory (Theory)](Data_science/Computation/Math/game_theory.theory.txt)
  - [matrices (Theory)](Data_science/Computation/Math/matrices.theory.txt)
  - [principal math (Theory)](Data_science/Computation/Math/principal_math.theory.txt)
  - [theorie des ensembles (Theory)](Data_science/Computation/Math/theorie_des_ensembles.theory.txt)
  - [theorie des nombres (Theory)](Data_science/Computation/Math/theorie_des_nombres.theory.txt)
- __Statistics__
  - [big data (Theory)](Data_science/Computation/Statistics/big_data.theory.txt)
  - [statistics theory (Theory)](Data_science/Computation/Statistics/statistics_theory.theory.txt)
  - [survey (Theory)](Data_science/Computation/Statistics/survey.theory.txt)

## Communication ##

### Messaging ###

- __Chat__
  - __General__
    - [gitter.im (SaaS)](Communication/Messaging/Chat/General/gitter.im.saas.txt)

## Business ##

### Law ###

- [licences (Theory)](Business/Law/licences.theory.txt)

### Office ###

- __Project management__
  - [Pivotal Tracker (SaaS)](Business/Office/Project_management/Pivotal Tracker.saas.txt)
  - [project management (Theory)](Business/Office/Project_management/project_management.theory.txt)
- __Team management__
  - [people management (Theory)](Business/Office/Team_management/people_management.theory.txt)
  - [team management (Theory)](Business/Office/Team_management/team_management.theory.txt)

### Promotion ###

- __Ads__
  - __Badges__
    - [shields.io (Images)](Business/Promotion/Ads/Badges/shields.io.images.txt)
- __SEO__
  - [SEO (Theory)](Business/Promotion/SEO/SEO.theory.txt)

## Design ##

### CSS ###

- __General__
  - __CSS in JavaScript__
    - [aphrodite (JavaScript)](Design/CSS/General/CSS_in_JavaScript/_aphrodite.javascript.txt)
    - [cssx (JavaScript)](Design/CSS/General/CSS_in_JavaScript/cssx.javascript.txt)
    - [react-css (React)](Design/CSS/General/CSS_in_JavaScript/react-css.react.txt)
    - [jss (JavaScript)](Design/CSS/General/CSS_in_JavaScript/jss.javascript.txt)
  - [CSS (Language)](Design/CSS/General/CSS.language.txt)

### Visual ###

- __Animations__
  - __Specific animations__
    - __General__
      - [animate.css (CSS)](Design/Visual/Animations/Specific_animations/General/animate.css.css.txt)
- __Typography__
  - [typography (Theory)](Design/Visual/Typography/typography.theory.txt)

## DevOps ##

### Configuration ###

- __Configuration data__
  - [dockerize (Docker)](DevOps/Configuration/Configuration_data/dockerize.docker.txt)
  - [docker-gen (Docker)](DevOps/Configuration/Configuration_data/docker-gen.docker.txt)
  - [rc (Node)](DevOps/Configuration/Configuration_data/rc.node.txt)
- __Configuration management__
  - [opswork (AWS)](DevOps/Configuration/Configuration_management/opswork.aws.txt)

### Deployment ###

- __Continuous integration__
  - [travis (SaaS)](DevOps/Deployment/Continuous_integration/travis.saas.txt)
  - [docker cloud (Docker)](DevOps/Deployment/Continuous_integration/docker_cloud.docker.txt)
- __Deployment general__
  - __Deploying__
    - [12 factor (Theory)](DevOps/Deployment/Deployment_general/Deploying/12_factor.theory.txt)
    - [installating files (Theory)](DevOps/Deployment/Deployment_general/Deploying/installating_files.theory.txt)
  - __On premise__
    - [directconnect (AWS)](DevOps/Deployment/Deployment_general/On_premise/directconnect.aws.txt)

### Infrastructure ###

- __CDN__
  - [cloudfront (AWS)](DevOps/Infrastructure/CDN/cloudfront.aws.txt)
- __IaaS__
  - [ec2 (AWS)](DevOps/Infrastructure/IaaS/ec2.aws.txt)
  - [AWS (SaaS)](DevOps/Infrastructure/IaaS/AWS.saas.txt)
- __PaaS__
  - [beanstalk (AWS)](DevOps/Infrastructure/PaaS/beanstalk.aws.txt)
  - [cloudformation (AWS)](DevOps/Infrastructure/PaaS/cloudformation.aws.txt)
- __SaaS__
  - [Google APIs (SaaS)](DevOps/Infrastructure/SaaS/Google_APIs.saas.txt)

### Supervision ###

- __Cluster orchestration__
  - [autoscaling (AWS)](DevOps/Supervision/Cluster_orchestration/autoscaling.aws.txt)
  - [docker swarm (Docker)](DevOps/Supervision/Cluster_orchestration/docker_swarm.docker.txt)
  - [kubernetes (CLI)](DevOps/Supervision/Cluster_orchestration/kubernetes.cli.txt)
- __Process supervisor__
  - [forever (Node CLI)](DevOps/Supervision/Process_supervisor/_forever.node_cli.txt)
  - [pm2 (Node CLI)](DevOps/Supervision/Process_supervisor/pm2.node_cli.txt)

### Virtualization ###

- __Containers__
  - __Core abstraction__
    - [docker (CLI)](DevOps/Virtualization/Containers/Core_abstraction/docker.cli.txt)
    - [docker compose (Docker)](DevOps/Virtualization/Containers/Core_abstraction/docker_compose.docker.txt)
  - [containers (Theory)](DevOps/Virtualization/Containers/containers.theory.txt)

## Languages ##

### C ###

- __Compiling__
  - __gcc__
    - [cpp (CLI)](Languages/C/Compiling/gcc/cpp.cli.txt)
    - [feature test macro (CLI)](Languages/C/Compiling/gcc/feature_test_macro.cli.txt)
    - [gcc (CLI)](Languages/C/Compiling/gcc/gcc.cli.txt)
    - [gcc optimization (CLI)](Languages/C/Compiling/gcc/gcc_optimization.cli.txt)
- [C (Language)](Languages/C/C.language.txt)
- [shared libraries (Theory)](Languages/C/shared_libraries.theory.txt)

### C++ ###

- [C++ (Language)](Languages/C++/C++.language.txt)

### Coding style ###

- __Linting__
  - __CSS__
    - [csslint (Node CLI)](Languages/Coding_style/Linting/CSS/csslint.node_cli.txt)
    - [immutable-css (Node CLI)](Languages/Coding_style/Linting/CSS/immutable-css.node_cli.txt)
    - [postcss-bem-linter (PostCSS)](Languages/Coding_style/Linting/CSS/postcss-bem-linter.postcss.txt)
    - [stylelint (Node CLI)](Languages/Coding_style/Linting/CSS/stylelint.node_cli.txt)
    - [scss-lint (CLI)](Languages/Coding_style/Linting/CSS/scss-lint.cli.txt)
  - __CoffeeScript__
    - [coffeelint (CoffeeScript)](Languages/Coding_style/Linting/CoffeeScript/coffeelint.coffeescript.txt)
  - __HTML__
    - [nu html checker (CLI)](Languages/Coding_style/Linting/HTML/nu_html_checker.cli.txt)
    - [htmlhint (Node CLI)](Languages/Coding_style/Linting/HTML/htmlhint.node_cli.txt)
  - __JavaScript__
    - [jshint (Node CLI)](Languages/Coding_style/Linting/JavaScript/jshint.node_cli.txt)
    - [w3cjs (Node)](Languages/Coding_style/Linting/JavaScript/w3cjs.node.txt)
  - __JavaScript CSS__
    - [hound (SaaS)](Languages/Coding_style/Linting/JavaScript_CSS/hound.saas.txt)

### Go ###

- [go (Language)](Languages/Go/go.language.txt)

### Inter language ###

- __Version migration__
  - __JavaScript__
    - [babel (Node CLI)](Languages/Inter_language/Version_migration/JavaScript/babel.node_cli.txt)

### JavaScript ###

- __Data binding__
  - [stickit (Backbone)](Languages/JavaScript/Data_binding/stickit.backbone.txt)
- __JavaScript core__
  - [JavaScript (Language)](Languages/JavaScript/JavaScript_core/JavaScript.language.txt)
  - __Transpiler__
    - [coffeescript (Language)](Languages/JavaScript/JavaScript_core/Transpiler/coffeescript.language.txt)
    - [flow (Language)](Languages/JavaScript/JavaScript_core/Transpiler/flow.language.txt)
- __JavaScript frameworks__
  - __View__
    - __One way data binding__
      - __Virtual DOM__
        - __React__
          - [backbone-react-component (React)](Languages/JavaScript/JavaScript_frameworks/View/One_way_data_binding/Virtual_DOM/React/backbone-react-component.react.txt)
          - [react (JavaScript)](Languages/JavaScript/JavaScript_frameworks/View/One_way_data_binding/Virtual_DOM/React/react.javascript.txt)
          - [react-helmet (React)](Languages/JavaScript/JavaScript_frameworks/View/One_way_data_binding/Virtual_DOM/React/react-helmet.react.txt)
          - [react-engine (React)](Languages/JavaScript/JavaScript_frameworks/View/One_way_data_binding/Virtual_DOM/React/react-engine.react.txt)
  - __MVC__
    - __Minimalistic__
      - __Backbone__
        - [backbone.collectionsubset (Backbone)](Languages/JavaScript/JavaScript_frameworks/MVC/Minimalistic/Backbone/backbone.collectionsubset.backbone.txt)
        - [backbone marionette (JavaScript)](Languages/JavaScript/JavaScript_frameworks/MVC/Minimalistic/Backbone/backbone_marionette.javascript.txt)
    - __Opiniated__
      - [angular (JavaScript)](Languages/JavaScript/JavaScript_frameworks/MVC/Opiniated/angular.javascript.txt)
- __Node__
  - [nodejs (JavaScript)](Languages/JavaScript/Node/nodejs.javascript.txt)
- __State management__
  - __Flux__
    - __Redux__
      - [redux-actions (Redux)](Languages/JavaScript/State_management/Flux/Redux/redux-actions.redux.txt)
      - [redux-thunk (Redux)](Languages/JavaScript/State_management/Flux/Redux/redux-thunk.redux.txt)
      - [redux-storage (Redux)](Languages/JavaScript/State_management/Flux/Redux/redux-storage.redux.txt)
      - [redux (Flux)](Languages/JavaScript/State_management/Flux/Redux/redux.flux.txt)
      - [redux-undo (Redux)](Languages/JavaScript/State_management/Flux/Redux/redux-undo.redux.txt)
    - [flux (JavaScript)](Languages/JavaScript/State_management/Flux/flux.javascript.txt)
    - [react-refetch (Flux)](Languages/JavaScript/State_management/Flux/react-refetch.flux.txt)

### Language processing ###

- __Beautifiers__
  - __CSS__
    - __General__
      - [stylefmt (Node CLI)](Languages/Language_processing/Beautifiers/CSS/General/_stylefmt.node_cli.txt)
      - [csscomb (Node CLI)](Languages/Language_processing/Beautifiers/CSS/General/csscomb.node_cli.txt)
      - [perfectionist (Node CLI)](Languages/Language_processing/Beautifiers/CSS/General/_perfectionist.node_cli.txt)
    - __Sorting__
      - [css-declaration-sorter (Node CLI)](Languages/Language_processing/Beautifiers/CSS/Sorting/css-declaration-sorter.node_cli.txt)
      - [postcss-sorting (PostCSS)](Languages/Language_processing/Beautifiers/CSS/Sorting/postcss-sorting.postcss.txt)
  - __JavaScript__
    - [uglify beautify (Node CLI)](Languages/Language_processing/Beautifiers/JavaScript/uglify_beautify.node_cli.txt)
- __Minification__
  - __HTML__
    - [tidy-html5 (CLI)](Languages/Language_processing/Minification/HTML/tidy-html5.cli.txt)
  - __CSS__
    - [cleancss (Node CLI)](Languages/Language_processing/Minification/CSS/_cleancss.node_cli.txt)
    - [csso (Node CLI)](Languages/Language_processing/Minification/CSS/_csso.node_cli.txt)
    - [cssnano (Node CLI)](Languages/Language_processing/Minification/CSS/cssnano.node_cli.txt)
  - __JavaScript__
    - [Uglify (Node CLI)](Languages/Language_processing/Minification/JavaScript/Uglify.node_cli.txt)
- __Post processing__
  - __CSS__
    - [less (Language)](Languages/Language_processing/Post_processing/CSS/_less.language.txt)
    - [sass (Language)](Languages/Language_processing/Post_processing/CSS/_sass.language.txt)
    - [compass (Sass)](Languages/Language_processing/Post_processing/CSS/_compass.sass.txt)
    - [stylus (Language)](Languages/Language_processing/Post_processing/CSS/_stylus.language.txt)
    - [postcss (Language)](Languages/Language_processing/Post_processing/CSS/postcss.language.txt)

### Metaprogramming ###

- __Parsing__
  - __Specific language__
    - __CSS__
      - [parser-lib (Node)](Languages/Metaprogramming/Parsing/Specific_language/CSS/parser-lib.node.txt)
      - [reworkcss (Node)](Languages/Metaprogramming/Parsing/Specific_language/CSS/reworkcss.node.txt)
      - [gonzales-pe (Node)](Languages/Metaprogramming/Parsing/Specific_language/CSS/gonzales-pe.node.txt)
  - [parsing (Theory)](Languages/Metaprogramming/Parsing/parsing.theory.txt)

### PHP ###

- [PHP (Language)](Languages/PHP/PHP.language.txt)

### Python ###

- [Python (Language)](Languages/Python/Python.language.txt)

### R ###

- [R (Language)](Languages/R/R.language.txt)

### Static analysis ###

- __Complexity size analysis__
  - __JavaScript__
    - [plato (Node CLI)](Languages/Static_analysis/Complexity_size_analysis/JavaScript/plato.node_cli.txt)
- __Dead code__
  - __CSS__
    - [mincss (Node CLI)](Languages/Static_analysis/Dead_code/CSS/_mincss.node_cli.txt)
    - [uncss (Node CLI)](Languages/Static_analysis/Dead_code/CSS/uncss.node_cli.txt)
- __General__
  - __Multiple languages__
    - [codeclimate (SaaS)](Languages/Static_analysis/General/Multiple_languages/codeclimate.saas.txt)
  - __CSS__
    - [cssstats (Node CLI)](Languages/Static_analysis/General/CSS/_cssstats.node_cli.txt)
    - [stylestats analyze-css (Node CLI)](Languages/Static_analysis/General/CSS/stylestats_analyze-css.node_cli.txt)

### VBA ###

- [Excel Formulas (Language)](Languages/VBA/Excel_Formulas.language.txt)
- [Excel objet model (Language)](Languages/VBA/Excel_objet_model.language.txt)
- [PowerPoint object model (Language)](Languages/VBA/PowerPoint_object_model.language.txt)
- [VBA (Language)](Languages/VBA/VBA.language.txt)

### x86 ###

- __Assembler__
  - [nasm (CLI)](Languages/x86/Assembler/nasm.cli.txt)
- [MMX SSE (Language)](Languages/x86/MMX_SSE.language.txt)
- [x86 (Language)](Languages/x86/x86.language.txt)
- [x86 64 (Language)](Languages/x86/x86_64.language.txt)
- [x86 General (Language)](Languages/x86/x86_General.language.txt)
- [x86 C compilation (Language)](Languages/x86/x86_C_compilation.language.txt)
- [x86 Segmentation Paging Tasks (Language)](Languages/x86/x86_Segmentation_Paging_Tasks.language.txt)
- [x86 encodage opcodes (Language)](Languages/x86/x86_encodage_opcodes.language.txt)
- [x86 extensions (Language)](Languages/x86/x86_extensions.language.txt)
- [x87 (Language)](Languages/x86/x87.language.txt)

## Multimedia ##

### Advanced graphics ###

- __Game__
  - __Design gamification__
    - [game design (Theory)](Multimedia/Advanced_graphics/Game/Design_gamification/game_design.theory.txt)
  - __Engines__
    - __2D__
      - __SDL__
        - [sdl (C)](Multimedia/Advanced_graphics/Game/Engines/2D/SDL/sdl.c.txt)
      - __SFML__
        - [sfml (C++)](Multimedia/Advanced_graphics/Game/Engines/2D/SFML/sfml.c++.txt)
        - [sfml graphics (C++)](Multimedia/Advanced_graphics/Game/Engines/2D/SFML/sfml_graphics.c++.txt)
        - [sfml audio (C++)](Multimedia/Advanced_graphics/Game/Engines/2D/SFML/sfml_audio.c++.txt)
        - [sfml network (C++)](Multimedia/Advanced_graphics/Game/Engines/2D/SFML/sfml_network.c++.txt)
        - [sfml system (C++)](Multimedia/Advanced_graphics/Game/Engines/2D/SFML/sfml_system.c++.txt)
        - [sfml window (C++)](Multimedia/Advanced_graphics/Game/Engines/2D/SFML/sfml_window.c++.txt)

### Geospatial ###

- __IP geolocation__
  - [geoip-lite (Node)](Multimedia/Geospatial/IP_geolocation/geoip-lite.node.txt)

### Graphics ###

- __3D__
  - __OpenGL__
    - [opengl (C)](Multimedia/Graphics/3D/OpenGL/opengl.c.txt)

### Images ###

- __Common images__
  - __Icons__
    - [zocial (CSS Fonts)](Multimedia/Images/Common_images/Icons/zocial.css_fonts.txt)
- __Favicon__
  - __Manipulation__
    - [favico.js (JavaScript)](Multimedia/Images/Favicon/Manipulation/favico.js.javascript.txt)
  - __Serving__
    - [serve-favicon (Express)](Multimedia/Images/Favicon/Serving/serve-favicon.express.txt)
- __Image display__
  - __Carousel__
    - [cycle2 (jQuery)](Multimedia/Images/Image_display/Carousel/_cycle2.jquery.txt)
    - [slick (jQuery)](Multimedia/Images/Image_display/Carousel/slick.jquery.txt)
  - __Lightbox__
    - [magnificpopup (jQuery)](Multimedia/Images/Image_display/Lightbox/magnificpopup.jquery.txt)
- __Image manipulation__
  - __Info__
    - [image-size (Node)](Multimedia/Images/Image_manipulation/Info/image-size.node.txt)
  - __Diff__
    - [resemble.js (Node)](Multimedia/Images/Image_manipulation/Diff/resemble.js.node.txt)
  - __Minification__
    - [imagemin (Node CLI)](Multimedia/Images/Image_manipulation/Minification/imagemin.node_cli.txt)

### Media ###

- __Audio__
  - [audio rates (Theory)](Multimedia/Media/Audio/audio_rates.theory.txt)

## Dev helpers ##

### Automation ###

- __Build automation__
  - __Autotools__
    - [autotools (CLI)](Dev_helpers/Automation/Build_automation/Autotools/autotools.cli.txt)
    - [make (CLI)](Dev_helpers/Automation/Build_automation/Autotools/make.cli.txt)
  - [grunt (JavaScript)](Dev_helpers/Automation/Build_automation/_grunt.javascript.txt)
  - [cmake (CLI)](Dev_helpers/Automation/Build_automation/cmake.cli.txt)
  - [gulp (JavaScript)](Dev_helpers/Automation/Build_automation/gulp.javascript.txt)
- __Desktop automation__
  - __Screenshots__
    - [webshot (Node)](Dev_helpers/Automation/Desktop_automation/Screenshots/webshot.node.txt)
  - [copy-paste (Node)](Dev_helpers/Automation/Desktop_automation/copy-paste.node.txt)
  - [open (Node)](Dev_helpers/Automation/Desktop_automation/open.node.txt)
- __Live reloading__
  - [livereload (Node)](Dev_helpers/Automation/Live_reloading/livereload.node.txt)
  - [nodemon (Node)](Dev_helpers/Automation/Live_reloading/nodemon.node.txt)
- __Scaffolding__
  - [yeoman (CLI)](Dev_helpers/Automation/Scaffolding/yeoman.cli.txt)

### Coding ###

- __Documentation__
  - __From comments__
    - [jsdoc (JavaScript)](Dev_helpers/Coding/Documentation/From_comments/jsdoc.javascript.txt)
    - [doxygen (Many)](Dev_helpers/Coding/Documentation/From_comments/doxygen.many.txt)
  - __UI component__
    - __Tutorial__
      - [torturial (jQuery)](Dev_helpers/Coding/Documentation/UI_component/Tutorial/torturial.jquery.txt)
- __Source code__
  - [organisation sources (Theory)](Dev_helpers/Coding/Source_code/organisation_sources.theory.txt)
- __Version control__
  - __Git__
    - [VCS (Theory)](Dev_helpers/Coding/Version_control/Git/VCS.theory.txt)
    - [git (CLI)](Dev_helpers/Coding/Version_control/Git/git.cli.txt)
  - __GitHub__
    - [github (SaaS)](Dev_helpers/Coding/Version_control/GitHub/github.saas.txt)

### Insights ###

- __Logging__
  - __Aggregator__
    - [cloudwatch logs (AWS)](Dev_helpers/Insights/Logging/Aggregator/cloudwatch_logs.aws.txt)
  - __Automatic logging__
    - __Network interaction__
      - [cloudtrail (AWS)](Dev_helpers/Insights/Logging/Automatic_logging/Network_interaction/cloudtrail.aws.txt)
    - __Errors__
      - [errorhandler (Express)](Dev_helpers/Insights/Logging/Automatic_logging/Errors/errorhandler.express.txt)
  - __Beautifying__
    - [createerror (Node)](Dev_helpers/Insights/Logging/Beautifying/createerror.node.txt)
  - __Logger__
    - __Server side__
      - [debug (Node)](Dev_helpers/Insights/Logging/Logger/Server_side/debug.node.txt)
      - [winston (Node)](Dev_helpers/Insights/Logging/Logger/Server_side/winston.node.txt)
      - [log4js (Node)](Dev_helpers/Insights/Logging/Logger/Server_side/_log4js.node.txt)
      - [morgan (Express)](Dev_helpers/Insights/Logging/Logger/Server_side/_morgan.express.txt)
- __Monitoring__
  - __Custom metrics__
    - __Alerting__
      - [vitalsigns (Node)](Dev_helpers/Insights/Monitoring/Custom_metrics/Alerting/vitalsigns.node.txt)
  - __Host metrics__
    - __Collecting dashboard__
      - [cloudwatch (AWS)](Dev_helpers/Insights/Monitoring/Host_metrics/Collecting_dashboard/cloudwatch.aws.txt)

### Quality assurance ###

- __Debugging__
  - __General debugger__
    - __Server side__
      - [bashdb (C C++ x86)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Server_side/bashdb.c_c++_x86.txt)
      - [gdb (C C++ x86)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Server_side/gdb.c_c++_x86.txt)
      - [xdebug (PHP)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Server_side/xdebug.php.txt)
      - [nm (x86)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Server_side/nm.x86.txt)
      - [express-debug (Express)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Server_side/express-debug.express.txt)
    - __Browser__
      - [react-devtools (React)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Browser/react-devtools.react.txt)
      - [about (Identifier)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Browser/about.identifier.txt)
      - [redux-devtools (Redux)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Browser/redux-devtools.redux.txt)
      - [view-source (Identifier)](Dev_helpers/Quality_assurance/Debugging/General_debugger/Browser/view-source.identifier.txt)
- __Testing__
  - __Assertions__
    - __HTTP__
      - [supertest (Node)](Dev_helpers/Quality_assurance/Testing/Assertions/HTTP/supertest.node.txt)
    - [chai (Node)](Dev_helpers/Quality_assurance/Testing/Assertions/chai.node.txt)
  - __Browser testing__
    - __Selenium__
      - __Runner__
        - [browserstack (SaaS)](Dev_helpers/Quality_assurance/Testing/Browser_testing/Selenium/Runner/browserstack.saas.txt)
        - [saucelabs (SaaS)](Dev_helpers/Quality_assurance/Testing/Browser_testing/Selenium/Runner/saucelabs.saas.txt)
        - [selenium webdriver (CLI)](Dev_helpers/Quality_assurance/Testing/Browser_testing/Selenium/Runner/selenium_webdriver.cli.txt)
      - __Client__
        - [selenium-webdriver (Node)](Dev_helpers/Quality_assurance/Testing/Browser_testing/Selenium/Client/selenium-webdriver.node.txt)
        - [wd.js (Node)](Dev_helpers/Quality_assurance/Testing/Browser_testing/Selenium/Client/wd.js.node.txt)
  - __Coverage__
    - [istanbul (Node CLI)](Dev_helpers/Quality_assurance/Testing/Coverage/istanbul.node_cli.txt)
    - [coveralls (SaaS)](Dev_helpers/Quality_assurance/Testing/Coverage/coveralls.saas.txt)
  - __Data-driven__
    - [faker.js (JavaScript)](Dev_helpers/Quality_assurance/Testing/Data-driven/faker.js.javascript.txt)
  - __Fuzz__
    - [big-list-of-naughty-strings (JSON TXT)](Dev_helpers/Quality_assurance/Testing/Fuzz/big-list-of-naughty-strings.json_txt.txt)
  - __Mocking__
    - __Module loading__
      - [jest (Jasmine)](Dev_helpers/Quality_assurance/Testing/Mocking/Module_loading/jest.jasmine.txt)
    - __Stubs spies__
      - [sinon (Node)](Dev_helpers/Quality_assurance/Testing/Mocking/Stubs_spies/sinon.node.txt)
    - __HTTP__
      - __Server side__
        - __Request response__
          - [node-mocks-http (Node)](Dev_helpers/Quality_assurance/Testing/Mocking/HTTP/Server_side/Request_response/node-mocks-http.node.txt)
        - __Response__
          - [nock (Node)](Dev_helpers/Quality_assurance/Testing/Mocking/HTTP/Server_side/Response/nock.node.txt)
    - __Specific framework__
      - [enzyme (React)](Dev_helpers/Quality_assurance/Testing/Mocking/Specific_framework/enzyme.react.txt)
  - __Stress__
    - [gremlins.js (JavaScript)](Dev_helpers/Quality_assurance/Testing/Stress/gremlins.js.javascript.txt)
  - __Test framework__
    - [karma (CLI)](Dev_helpers/Quality_assurance/Testing/Test_framework/karma.cli.txt)
  - __Test runners__
    - [jasmine (Node CLI)](Dev_helpers/Quality_assurance/Testing/Test_runners/_jasmine.node_cli.txt)
    - [qunit (CLI)](Dev_helpers/Quality_assurance/Testing/Test_runners/_qunit.cli.txt)
    - [mocha (Node CLI)](Dev_helpers/Quality_assurance/Testing/Test_runners/mocha.node_cli.txt)
  - __Visual__
    - [wraith (Node)](Dev_helpers/Quality_assurance/Testing/Visual/_wraith.node.txt)
    - [argus-eyes (CLI)](Dev_helpers/Quality_assurance/Testing/Visual/argus-eyes.cli.txt)
    - [phantomcss (Node)](Dev_helpers/Quality_assurance/Testing/Visual/_phantomcss.node.txt)
  - [testing (Summary)](Dev_helpers/Quality_assurance/Testing/testing.summary.txt)
  - [testing (Theory)](Dev_helpers/Quality_assurance/Testing/testing.theory.txt)

## Networking ##

### Networking protocols ###

- __DNS__
  - [DNS (Protocol)](Networking/Networking_protocols/DNS/DNS.protocol.txt)
  - __Registration__
    - [route53 (AWS)](Networking/Networking_protocols/DNS/Registration/route53.aws.txt)
- __IP__
  - [IP (Protocol)](Networking/Networking_protocols/IP/IP.protocol.txt)
- __Load balancing__
  - __Load balancer__
    - [elb (AWS)](Networking/Networking_protocols/Load_balancing/Load_balancer/elb.aws.txt)
- __Networking general__
  - [network (Theory)](Networking/Networking_protocols/Networking_general/network.theory.txt)
  - [protocols (Theory)](Networking/Networking_protocols/Networking_general/protocols.theory.txt)
- __Phones__
  - [tel uri scheme (Identifier)](Networking/Networking_protocols/Phones/tel_uri_scheme.identifier.txt)
- __Proxy__
  - __HTTP__
    - [proxy-addr (Node)](Networking/Networking_protocols/Proxy/HTTP/proxy-addr.node.txt)
    - [http-proxy (Node)](Networking/Networking_protocols/Proxy/HTTP/http-proxy.node.txt)
- __SSL TLS__
  - __HTTPS__
    - [HTTPS (Protocol)](Networking/Networking_protocols/SSL_TLS/HTTPS/HTTPS.protocol.txt)
  - [SSL (Protocol)](Networking/Networking_protocols/SSL_TLS/SSL.protocol.txt)
  - __Library__
    - [express-enforces-ssl (Express)](Networking/Networking_protocols/SSL_TLS/Library/express-enforces-ssl.express.txt)
- __Service discovery__
  - [DHCP (Protocol)](Networking/Networking_protocols/Service_discovery/DHCP.protocol.txt)
- __TCP__
  - [TCP (Protocol)](Networking/Networking_protocols/TCP/TCP.protocol.txt)
- __UDP__
  - [UDP (Protocol)](Networking/Networking_protocols/UDP/UDP.protocol.txt)

## Platforms ##

### Browser ###

- __DOM__
  - __Abstraction__
    - [jsdom (Node)](Platforms/Browser/DOM/Abstraction/jsdom.node.txt)
    - [rackt history (JavaScript)](Platforms/Browser/DOM/Abstraction/rackt_history.javascript.txt)
  - [DOM (JavaScript)](Platforms/Browser/DOM/DOM.javascript.txt)
  - __Manipulation__
    - [jQuery cheerio (JavaScript)](Platforms/Browser/DOM/Manipulation/jQuery_cheerio.javascript.txt)
  - __Virtual DOM__
    - [react-templates (React)](Platforms/Browser/DOM/Virtual_DOM/react-templates.react.txt)
- __Browser extensions__
  - __Chrome__
    - [Chrome extensions apps (JavaScript)](Platforms/Browser/Browser_extensions/Chrome/Chrome_extensions_apps.javascript.txt)
- __Headless browser__
  - [casperjs (Node CLI)](Platforms/Browser/Headless_browser/casperjs.node_cli.txt)
  - [phantomjs (Node CLI)](Platforms/Browser/Headless_browser/phantomjs.node_cli.txt)

### Desktop ###

- __Desktop only features__
  - __Notifications__
    - [growl (Node)](Platforms/Desktop/Desktop_only_features/Notifications/growl.node.txt)
- __OS__
  - __Executable__
    - [elf (Format)](Platforms/Desktop/OS/Executable/elf.format.txt)
    - [object formats (Format)](Platforms/Desktop/OS/Executable/object_formats.format.txt)
  - __OS Kernel__
    - [OS Boot kernel (Theory)](Platforms/Desktop/OS/OS_Kernel/OS_Boot_kernel.theory.txt)
    - [OS filesystem (Theory)](Platforms/Desktop/OS/OS_Kernel/OS_filesystem.theory.txt)
    - __Process__
      - [process (Theory)](Platforms/Desktop/OS/OS_Kernel/Process/process.theory.txt)
      - [loading time (Format)](Platforms/Desktop/OS/OS_Kernel/Process/loading_time.format.txt)
    - [OS Gestion memoire (Theory)](Platforms/Desktop/OS/OS_Kernel/OS_Gestion_memoire.theory.txt)
  - __Partitions__
    - [CHS LBA (Theory)](Platforms/Desktop/OS/Partitions/CHS_LBA.theory.txt)
    - [type partitions (Format)](Platforms/Desktop/OS/Partitions/type_partitions.format.txt)
    - [MBR (Format)](Platforms/Desktop/OS/Partitions/MBR.format.txt)
  - __System__
    - [CPU (Theory)](Platforms/Desktop/OS/System/CPU.theory.txt)
  - __Types__
    - [float fixed point (Format)](Platforms/Desktop/OS/Types/float_fixed_point.format.txt)
    - [BCD (Format)](Platforms/Desktop/OS/Types/BCD.format.txt)
    - [signedness binaire (Format)](Platforms/Desktop/OS/Types/signedness_binaire.format.txt)
    - [little big endian (Format)](Platforms/Desktop/OS/Types/little_big_endian.format.txt)
  - [architectures (Theory)](Platforms/Desktop/OS/architectures.theory.txt)
  - [calcul binaire (Algorithm)](Platforms/Desktop/OS/calcul_binaire.algorithm.txt)
  - [taille octet bits bytes (Theory)](Platforms/Desktop/OS/taille_octet_bits_bytes.theory.txt)

### Interoperability ###

- __Browser__
  - __Browser list__
    - [browserslist (Node CLI)](Platforms/Interoperability/Browser/Browser_list/browserslist.node_cli.txt)
  - __CSS__
    - __Linting__
      - [doiuse (Node CLI)](Platforms/Interoperability/Browser/CSS/Linting/doiuse.node_cli.txt)
    - __Transpiler__
      - [cssnext (PostCSS)](Platforms/Interoperability/Browser/CSS/Transpiler/cssnext.postcss.txt)
      - [autoprefixer (Node CLI)](Platforms/Interoperability/Browser/CSS/Transpiler/autoprefixer.node_cli.txt)
    - __Normalizer__
      - [normalize.css (CSS)](Platforms/Interoperability/Browser/CSS/Normalizer/normalize.css.css.txt)
  - __Device identification__
    - [express-device (Express)](Platforms/Interoperability/Browser/Device_identification/express-device.express.txt)
    - [session.js (JavaScript)](Platforms/Interoperability/Browser/Device_identification/session.js.javascript.txt)
  - __Feature support__
    - [modernizr (JavaScript)](Platforms/Interoperability/Browser/Feature_support/modernizr.javascript.txt)
    - [feature.js (JavaScript)](Platforms/Interoperability/Browser/Feature_support/_feature.js.javascript.txt)
    - [caniuse (JSON)](Platforms/Interoperability/Browser/Feature_support/caniuse.json.txt)

### Mobile ###

- __Mobile only features__
  - __Notifications__
    - [sns (AWS)](Platforms/Mobile/Mobile_only_features/Notifications/sns.aws.txt)
- __Mobile responsiveness__
  - __Mobile menu__
    - [meny (JavaScript)](Platforms/Mobile/Mobile_responsiveness/Mobile_menu/meny.javascript.txt)
    - [snap.js (JavaScript)](Platforms/Mobile/Mobile_responsiveness/Mobile_menu/snap.js.javascript.txt)
  - [mobile strategy (Theory)](Platforms/Mobile/Mobile_responsiveness/mobile_strategy.theory.txt)

### Terminal ###

- __CLI__
  - __Input__
    - [bytes (Node)](Platforms/Terminal/CLI/Input/bytes.node.txt)
    - [ms (Node CLI)](Platforms/Terminal/CLI/Input/ms.node_cli.txt)
    - [minimist (Node)](Platforms/Terminal/CLI/Input/minimist.node.txt)
  - __Output__
    - __Colors__
      - [chalk (Node)](Platforms/Terminal/CLI/Output/Colors/chalk.node.txt)
    - __Prompt__
      - [inquirer (Node)](Platforms/Terminal/CLI/Output/Prompt/inquirer.node.txt)
- __Terminal general__
  - __Remote__
    - __SSH__
      - [SSH (Protocol)](Platforms/Terminal/Terminal_general/Remote/SSH/SSH.protocol.txt)

## To sort ##

### Utilities to sort ###

- __C__
  - __Standard library__
    - __C89__
      - [assert](To_sort/Utilities_to_sort/C/Standard_library/C89/assert.txt)
      - [ctype](To_sort/Utilities_to_sort/C/Standard_library/C89/ctype.txt)
      - [float](To_sort/Utilities_to_sort/C/Standard_library/C89/float.txt)
      - [limits](To_sort/Utilities_to_sort/C/Standard_library/C89/limits.txt)
      - [locale](To_sort/Utilities_to_sort/C/Standard_library/C89/locale.txt)
      - [math](To_sort/Utilities_to_sort/C/Standard_library/C89/math.txt)
      - [errno](To_sort/Utilities_to_sort/C/Standard_library/C89/errno.txt)
      - [setjmp](To_sort/Utilities_to_sort/C/Standard_library/C89/setjmp.txt)
      - [signal](To_sort/Utilities_to_sort/C/Standard_library/C89/signal.txt)
      - [stdarg](To_sort/Utilities_to_sort/C/Standard_library/C89/stdarg.txt)
      - [stddef](To_sort/Utilities_to_sort/C/Standard_library/C89/stddef.txt)
      - [stdio](To_sort/Utilities_to_sort/C/Standard_library/C89/stdio.txt)
      - [stdlib](To_sort/Utilities_to_sort/C/Standard_library/C89/stdlib.txt)
      - [string](To_sort/Utilities_to_sort/C/Standard_library/C89/string.txt)
      - [time](To_sort/Utilities_to_sort/C/Standard_library/C89/time.txt)
    - __C99__
      - [inttypes](To_sort/Utilities_to_sort/C/Standard_library/C99/inttypes.txt)
      - [stdbool](To_sort/Utilities_to_sort/C/Standard_library/C99/stdbool.txt)
      - [stdint](To_sort/Utilities_to_sort/C/Standard_library/C99/stdint.txt)
    - __C95__
      - [iso646](To_sort/Utilities_to_sort/C/Standard_library/C95/iso646.txt)
      - [wctype](To_sort/Utilities_to_sort/C/Standard_library/C95/wctype.txt)
      - [wchar](To_sort/Utilities_to_sort/C/Standard_library/C95/wchar.txt)
  - __Glibc__
    - [IO filedescriptors](To_sort/Utilities_to_sort/C/Glibc/IO_filedescriptors.txt)
    - [IO memoire](To_sort/Utilities_to_sort/C/Glibc/IO_memoire.txt)
    - [IO normale](To_sort/Utilities_to_sort/C/Glibc/IO_normale.txt)
    - [TODO](To_sort/Utilities_to_sort/C/Glibc/TODO.txt)
    - [attributs fichiers](To_sort/Utilities_to_sort/C/Glibc/attributs_fichiers.txt)
    - [caracteres](To_sort/Utilities_to_sort/C/Glibc/caracteres.txt)
    - [communication interprocess](To_sort/Utilities_to_sort/C/Glibc/communication_interprocess.txt)
    - [dynamic allocation](To_sort/Utilities_to_sort/C/Glibc/dynamic_allocation.txt)
    - [encodage crypto](To_sort/Utilities_to_sort/C/Glibc/encodage_crypto.txt)
    - [erreurs](To_sort/Utilities_to_sort/C/Glibc/erreurs.txt)
    - [extension 64 bits](To_sort/Utilities_to_sort/C/Glibc/extension_64_bits.txt)
    - [fichiers temporaires](To_sort/Utilities_to_sort/C/Glibc/fichiers_temporaires.txt)
    - [goto](To_sort/Utilities_to_sort/C/Glibc/goto.txt)
    - [limites](To_sort/Utilities_to_sort/C/Glibc/limites.txt)
    - [options programme](To_sort/Utilities_to_sort/C/Glibc/options_programme.txt)
    - [program execution](To_sort/Utilities_to_sort/C/Glibc/program_execution.txt)
    - [repertoires](To_sort/Utilities_to_sort/C/Glibc/repertoires.txt)
    - [signaux](To_sort/Utilities_to_sort/C/Glibc/signaux.txt)
    - [strings](To_sort/Utilities_to_sort/C/Glibc/strings.txt)
    - [systeme de fichier](To_sort/Utilities_to_sort/C/Glibc/systeme_de_fichier.txt)
    - [time](To_sort/Utilities_to_sort/C/Glibc/time.txt)
    - [wchar wstr](To_sort/Utilities_to_sort/C/Glibc/wchar_wstr.txt)
- __C++__
  - __Standard library__
    - [bitset](To_sort/Utilities_to_sort/C++/Standard_library/bitset.txt)
    - [algorithm](To_sort/Utilities_to_sort/C++/Standard_library/algorithm.txt)
    - [containers](To_sort/Utilities_to_sort/C++/Standard_library/containers.txt)
    - [exception](To_sort/Utilities_to_sort/C++/Standard_library/exception.txt)
    - [functional](To_sort/Utilities_to_sort/C++/Standard_library/functional.txt)
    - [iterator](To_sort/Utilities_to_sort/C++/Standard_library/iterator.txt)
    - [limits](To_sort/Utilities_to_sort/C++/Standard_library/limits.txt)
    - [locale](To_sort/Utilities_to_sort/C++/Standard_library/locale.txt)
    - [memory](To_sort/Utilities_to_sort/C++/Standard_library/memory.txt)
    - [new](To_sort/Utilities_to_sort/C++/Standard_library/new.txt)
    - [streams](To_sort/Utilities_to_sort/C++/Standard_library/streams.txt)
    - [string](To_sort/Utilities_to_sort/C++/Standard_library/string.txt)
    - [typeinfo](To_sort/Utilities_to_sort/C++/Standard_library/typeinfo.txt)
    - [utility](To_sort/Utilities_to_sort/C++/Standard_library/utility.txt)
    - [valarray](To_sort/Utilities_to_sort/C++/Standard_library/valarray.txt)
  - __Boost__
    - [any](To_sort/Utilities_to_sort/C++/Boost/any.txt)
    - __Images__
      - [random (JPG)](To_sort/Utilities_to_sort/C++/Boost/Images/random.jpg)
    - [boost uuid](To_sort/Utilities_to_sort/C++/Boost/boost_uuid.txt)
    - [array](To_sort/Utilities_to_sort/C++/Boost/array.txt)
    - [boost](To_sort/Utilities_to_sort/C++/Boost/boost.txt)
    - [call traits](To_sort/Utilities_to_sort/C++/Boost/call_traits.txt)
    - [compressed pair](To_sort/Utilities_to_sort/C++/Boost/compressed_pair.txt)
    - [crc](To_sort/Utilities_to_sort/C++/Boost/crc.txt)
    - [concept check assert](To_sort/Utilities_to_sort/C++/Boost/concept_check_assert.txt)
    - [date time](To_sort/Utilities_to_sort/C++/Boost/date_time.txt)
    - [dynamic bitset](To_sort/Utilities_to_sort/C++/Boost/dynamic_bitset.txt)
    - [filesystem](To_sort/Utilities_to_sort/C++/Boost/filesystem.txt)
    - [function bind mem fn](To_sort/Utilities_to_sort/C++/Boost/function_bind_mem_fn.txt)
    - [hash](To_sort/Utilities_to_sort/C++/Boost/hash.txt)
    - [iterator](To_sort/Utilities_to_sort/C++/Boost/iterator.txt)
    - [lexical cast](To_sort/Utilities_to_sort/C++/Boost/lexical_cast.txt)
    - [random](To_sort/Utilities_to_sort/C++/Boost/random.txt)
    - [range algorithm](To_sort/Utilities_to_sort/C++/Boost/range_algorithm.txt)
    - [ref](To_sort/Utilities_to_sort/C++/Boost/ref.txt)
    - [serialization](To_sort/Utilities_to_sort/C++/Boost/serialization.txt)
    - [smart ptr](To_sort/Utilities_to_sort/C++/Boost/smart_ptr.txt)
    - [swap](To_sort/Utilities_to_sort/C++/Boost/swap.txt)
    - [thread](To_sort/Utilities_to_sort/C++/Boost/thread.txt)
    - [timer](To_sort/Utilities_to_sort/C++/Boost/timer.txt)
    - [tribool](To_sort/Utilities_to_sort/C++/Boost/tribool.txt)
    - [tuple](To_sort/Utilities_to_sort/C++/Boost/tuple.txt)
    - [type traits](To_sort/Utilities_to_sort/C++/Boost/type_traits.txt)
    - [variant](To_sort/Utilities_to_sort/C++/Boost/variant.txt)

### C++ ###

- __Gnome__
  - __Atkmm__
    - [atkmm](To_sort/C++/Gnome/Atkmm/atkmm.txt)
  - __Cairomm__
    - [cairomm](To_sort/C++/Gnome/Cairomm/cairomm.txt)
  - __Gdkmm__
    - [gdkmm](To_sort/C++/Gnome/Gdkmm/gdkmm.txt)
  - __GObject__
    - [GObject](To_sort/C++/Gnome/GObject/GObject.txt)
  - __Giomm__
    - [giomm](To_sort/C++/Gnome/Giomm/giomm.txt)
  - __Glibmm__
    - [Glibmm](To_sort/C++/Gnome/Glibmm/Glibmm.txt)
  - __Gtkmm__
    - [gtkmm](To_sort/C++/Gnome/Gtkmm/gtkmm.txt)
  - __Pangomm__
    - [pangomm](To_sort/C++/Gnome/Pangomm/pangomm.txt)
  - [glade](To_sort/C++/Gnome/glade.txt)
  - __libsigc++__
    - [libsigc++](To_sort/C++/Gnome/libsigc++/libsigc++.txt)
- [argument dependent lookup](To_sort/C++/argument_dependent_lookup.txt)
- [exception safety](To_sort/C++/exception_safety.txt)
- [generic programming](To_sort/C++/generic_programming.txt)
- [metaprogramming](To_sort/C++/metaprogramming.txt)
- [naming convention](To_sort/C++/naming_convention.txt)
- [optimization](To_sort/C++/optimization.txt)

### Bash Unix ###

- __Bash__
  - [bash variables](To_sort/Bash_Unix/Bash/bash_variables.txt)
  - [bash](To_sort/Bash_Unix/Bash/bash.txt)
  - [batch bash equivalences](To_sort/Bash_Unix/Bash/batch_bash_equivalences.txt)
  - [colorisation shell](To_sort/Bash_Unix/Bash/colorisation_shell.txt)
  - [common options](To_sort/Bash_Unix/Bash/common_options.txt)
  - [differences bash sh](To_sort/Bash_Unix/Bash/differences_bash_sh.txt)
  - [expansion susbitution](To_sort/Bash_Unix/Bash/expansion_susbitution.txt)
  - [differences versions bash](To_sort/Bash_Unix/Bash/differences_versions_bash.txt)
  - [fichiers configuration](To_sort/Bash_Unix/Bash/fichiers_configuration.txt)
  - [history](To_sort/Bash_Unix/Bash/history.txt)
  - [hotkeys console](To_sort/Bash_Unix/Bash/hotkeys_console.txt)
  - [prompt bash](To_sort/Bash_Unix/Bash/prompt_bash.txt)
  - [shell options](To_sort/Bash_Unix/Bash/shell_options.txt)
- __Commandes__
  - [7z](To_sort/Bash_Unix/Commandes/7z.txt)
  - [abs makepkg](To_sort/Bash_Unix/Commandes/abs_makepkg.txt)
  - [agrep](To_sort/Bash_Unix/Commandes/agrep.txt)
  - [alias unalias](To_sort/Bash_Unix/Commandes/alias_unalias.txt)
  - [at atq atrm batch](To_sort/Bash_Unix/Commandes/at_atq_atrm_batch.txt)
  - [awk](To_sort/Bash_Unix/Commandes/awk.txt)
  - [anacron](To_sort/Bash_Unix/Commandes/anacron.txt)
  - [basename dirname](To_sort/Bash_Unix/Commandes/basename_dirname.txt)
  - [cal ncal](To_sort/Bash_Unix/Commandes/cal_ncal.txt)
  - [cat tac](To_sort/Bash_Unix/Commandes/cat_tac.txt)
  - [cd](To_sort/Bash_Unix/Commandes/cd.txt)
  - [chkdupexe](To_sort/Bash_Unix/Commandes/chkdupexe.txt)
  - [chmod](To_sort/Bash_Unix/Commandes/chmod.txt)
  - [clear](To_sort/Bash_Unix/Commandes/clear.txt)
  - [cloud-init](To_sort/Bash_Unix/Commandes/cloud-init.txt)
  - [command builtin enable](To_sort/Bash_Unix/Commandes/command_builtin_enable.txt)
  - [cp mv](To_sort/Bash_Unix/Commandes/cp_mv.txt)
  - [cron crontab](To_sort/Bash_Unix/Commandes/cron_crontab.txt)
  - [csplit](To_sort/Bash_Unix/Commandes/csplit.txt)
  - [cut](To_sort/Bash_Unix/Commandes/cut.txt)
  - [date](To_sort/Bash_Unix/Commandes/date.txt)
  - [dd](To_sort/Bash_Unix/Commandes/dd.txt)
  - [dmesg](To_sort/Bash_Unix/Commandes/dmesg.txt)
  - [du](To_sort/Bash_Unix/Commandes/du.txt)
  - [echo](To_sort/Bash_Unix/Commandes/echo.txt)
  - [df](To_sort/Bash_Unix/Commandes/df.txt)
  - [env printenv](To_sort/Bash_Unix/Commandes/env_printenv.txt)
  - [expand unexpand](To_sort/Bash_Unix/Commandes/expand_unexpand.txt)
  - [factor](To_sort/Bash_Unix/Commandes/factor.txt)
  - [find](To_sort/Bash_Unix/Commandes/find.txt)
  - [fold](To_sort/Bash_Unix/Commandes/fold.txt)
  - [getopts getopt](To_sort/Bash_Unix/Commandes/getopts_getopt.txt)
  - [grep egrep fgrep rgrep](To_sort/Bash_Unix/Commandes/grep_egrep_fgrep_rgrep.txt)
  - [head tail](To_sort/Bash_Unix/Commandes/head_tail.txt)
  - [hash](To_sort/Bash_Unix/Commandes/hash.txt)
  - [help](To_sort/Bash_Unix/Commandes/help.txt)
  - [history](To_sort/Bash_Unix/Commandes/history.txt)
  - [iconv](To_sort/Bash_Unix/Commandes/iconv.txt)
  - [id](To_sort/Bash_Unix/Commandes/id.txt)
  - [info](To_sort/Bash_Unix/Commandes/info.txt)
  - [ipcalc](To_sort/Bash_Unix/Commandes/ipcalc.txt)
  - [kill](To_sort/Bash_Unix/Commandes/kill.txt)
  - [less](To_sort/Bash_Unix/Commandes/less.txt)
  - [line](To_sort/Bash_Unix/Commandes/line.txt)
  - [ln link](To_sort/Bash_Unix/Commandes/ln_link.txt)
  - [locate](To_sort/Bash_Unix/Commandes/locate.txt)
  - [look](To_sort/Bash_Unix/Commandes/look.txt)
  - [ls dir vdir](To_sort/Bash_Unix/Commandes/ls_dir_vdir.txt)
  - [lsattr chattr](To_sort/Bash_Unix/Commandes/lsattr_chattr.txt)
  - [man](To_sort/Bash_Unix/Commandes/man.txt)
  - [mapfile readarray](To_sort/Bash_Unix/Commandes/mapfile_readarray.txt)
  - [mesg](To_sort/Bash_Unix/Commandes/mesg.txt)
  - [mkdir](To_sort/Bash_Unix/Commandes/mkdir.txt)
  - [mkfifo](To_sort/Bash_Unix/Commandes/mkfifo.txt)
  - [mknod](To_sort/Bash_Unix/Commandes/mknod.txt)
  - [mktemp](To_sort/Bash_Unix/Commandes/mktemp.txt)
  - [more](To_sort/Bash_Unix/Commandes/more.txt)
  - [mount](To_sort/Bash_Unix/Commandes/mount.txt)
  - [mtrace](To_sort/Bash_Unix/Commandes/mtrace.txt)
  - [ncat](To_sort/Bash_Unix/Commandes/ncat.txt)
  - [nice renice](To_sort/Bash_Unix/Commandes/nice_renice.txt)
  - [nohup](To_sort/Bash_Unix/Commandes/nohup.txt)
  - [od hexdump hd](To_sort/Bash_Unix/Commandes/od_hexdump_hd.txt)
  - [pacman](To_sort/Bash_Unix/Commandes/pacman.txt)
  - [passwd](To_sort/Bash_Unix/Commandes/passwd.txt)
  - [paste join](To_sort/Bash_Unix/Commandes/paste_join.txt)
  - [pathchk](To_sort/Bash_Unix/Commandes/pathchk.txt)
  - [popd pushd dirs](To_sort/Bash_Unix/Commandes/popd_pushd_dirs.txt)
  - [printf](To_sort/Bash_Unix/Commandes/printf.txt)
  - [pwd](To_sort/Bash_Unix/Commandes/pwd.txt)
  - [read](To_sort/Bash_Unix/Commandes/read.txt)
  - [readlink](To_sort/Bash_Unix/Commandes/readlink.txt)
  - [rev](To_sort/Bash_Unix/Commandes/rev.txt)
  - [rm unlink](To_sort/Bash_Unix/Commandes/rm_unlink.txt)
  - [rmdir](To_sort/Bash_Unix/Commandes/rmdir.txt)
  - [sed](To_sort/Bash_Unix/Commandes/sed.txt)
  - [seq](To_sort/Bash_Unix/Commandes/seq.txt)
  - [shopt](To_sort/Bash_Unix/Commandes/shopt.txt)
  - [shred](To_sort/Bash_Unix/Commandes/shred.txt)
  - [shuf](To_sort/Bash_Unix/Commandes/shuf.txt)
  - [sleep](To_sort/Bash_Unix/Commandes/sleep.txt)
  - [sort](To_sort/Bash_Unix/Commandes/sort.txt)
  - [split](To_sort/Bash_Unix/Commandes/split.txt)
  - [stat](To_sort/Bash_Unix/Commandes/stat.txt)
  - [stdbuf](To_sort/Bash_Unix/Commandes/stdbuf.txt)
  - [sum cksum md5sum shasum](To_sort/Bash_Unix/Commandes/sum_cksum_md5sum_shasum.txt)
  - [sync](To_sort/Bash_Unix/Commandes/sync.txt)
  - [tar](To_sort/Bash_Unix/Commandes/tar.txt)
  - [tee](To_sort/Bash_Unix/Commandes/tee.txt)
  - [time times](To_sort/Bash_Unix/Commandes/time_times.txt)
  - [top](To_sort/Bash_Unix/Commandes/top.txt)
  - [touch](To_sort/Bash_Unix/Commandes/touch.txt)
  - [tr](To_sort/Bash_Unix/Commandes/tr.txt)
  - [trap](To_sort/Bash_Unix/Commandes/trap.txt)
  - [truncate](To_sort/Bash_Unix/Commandes/truncate.txt)
  - [tsort](To_sort/Bash_Unix/Commandes/tsort.txt)
  - [tty](To_sort/Bash_Unix/Commandes/tty.txt)
  - [type which](To_sort/Bash_Unix/Commandes/type_which.txt)
  - [ulimit](To_sort/Bash_Unix/Commandes/ulimit.txt)
  - [umask](To_sort/Bash_Unix/Commandes/umask.txt)
  - [uname arch](To_sort/Bash_Unix/Commandes/uname_arch.txt)
  - [uniq](To_sort/Bash_Unix/Commandes/uniq.txt)
  - [updatedb](To_sort/Bash_Unix/Commandes/updatedb.txt)
  - [upstart](To_sort/Bash_Unix/Commandes/upstart.txt)
  - [uptime](To_sort/Bash_Unix/Commandes/uptime.txt)
  - [watch](To_sort/Bash_Unix/Commandes/watch.txt)
  - [wc](To_sort/Bash_Unix/Commandes/wc.txt)
  - [whatis apropos](To_sort/Bash_Unix/Commandes/whatis_apropos.txt)
  - [whereis](To_sort/Bash_Unix/Commandes/whereis.txt)
  - [write wall](To_sort/Bash_Unix/Commandes/write_wall.txt)
  - [xargs](To_sort/Bash_Unix/Commandes/xargs.txt)
  - [xdotool](To_sort/Bash_Unix/Commandes/xdotool.txt)
  - [yes](To_sort/Bash_Unix/Commandes/yes.txt)
  - [zdump](To_sort/Bash_Unix/Commandes/zdump.txt)
  - [base64](To_sort/Bash_Unix/Commandes/base64.txt)
- [Options_avec ou sans whitespace](To_sort/Bash_Unix/Options_avec_ou_sans_whitespace.txt)
- [afaire unix](To_sort/Bash_Unix/afaire_unix.txt)
- [atime ctime mtime](To_sort/Bash_Unix/atime_ctime_mtime.txt)
- [buffering](To_sort/Bash_Unix/buffering.txt)
- [character block special files](To_sort/Bash_Unix/character_block_special_files.txt)
- [classe posix](To_sort/Bash_Unix/classe_posix.txt)
- [droits d acces](To_sort/Bash_Unix/droits_d_acces.txt)
- [fifo unamedpipe](To_sort/Bash_Unix/fifo_unamedpipe.txt)
- [human readable sizes](To_sort/Bash_Unix/human_readable_sizes.txt)
- [lock](To_sort/Bash_Unix/lock.txt)
- [newline](To_sort/Bash_Unix/newline.txt)
- [packets essentiels](To_sort/Bash_Unix/packets_essentiels.txt)
- [regexps](To_sort/Bash_Unix/regexps.txt)
- [repertoire dev](To_sort/Bash_Unix/repertoire_dev.txt)
- [sequence echappement backslash](To_sort/Bash_Unix/sequence_echappement_backslash.txt)
- [sequence echappement date](To_sort/Bash_Unix/sequence_echappement_date.txt)
- [signaux](To_sort/Bash_Unix/signaux.txt)
- [specifications](To_sort/Bash_Unix/specifications.txt)
- [taille des fichiers](To_sort/Bash_Unix/taille_des_fichiers.txt)
- [users and groups](To_sort/Bash_Unix/users_and_groups.txt)

## UX ##

### Accessibility ###

- __Empathy engineering__
  - [empathy engineering (Theory)](UX/Accessibility/Empathy_engineering/empathy_engineering.theory.txt)
- [accessibility (Theory)](UX/Accessibility/accessibility.theory.txt)

### Boxes ###

- __Modals__
  - [avgrund (jQuery)](UX/Boxes/Modals/_avgrund.jquery.txt)
- __Toast notification__
  - [angular growl 2 (Angular)](UX/Boxes/Toast_notification/angular_growl_2.angular.txt)

### Behavior ###

- __Analytics__
  - [analytics (Theory)](UX/Behavior/Analytics/analytics.theory.txt)
  - [angulartics (Angular)](UX/Behavior/Analytics/angulartics.angular.txt)
- __Offline__
  - [offline (JavaScript)](UX/Behavior/Offline/offline.javascript.txt)

### Forms ###

- __Form input__
  - __Autosize__
    - [autosize (JavaScript)](UX/Forms/Form_input/Autosize/autosize.javascript.txt)
- __Form select__
  - [select2 (jQuery)](UX/Forms/Form_select/select2.jquery.txt)
  - [chosen (jQuery)](UX/Forms/Form_select/_chosen.jquery.txt)
- __Form sliders__
  - [knob (jQuery)](UX/Forms/Form_sliders/knob.jquery.txt)
- __Progress bars__
  - [nprogress (JavaScript)](UX/Forms/Progress_bars/nprogress.javascript.txt)
- __Rich editor__
  - __Autocompletion__
    - __Inside input__
      - [typeahead.js (jQuery)](UX/Forms/Rich_editor/Autocompletion/Inside_input/typeahead.js.jquery.txt)
  - __RTF__
    - [redactor (jQuery)](UX/Forms/Rich_editor/RTF/_redactor.jquery.txt)
    - [ckeditor (JavaScript)](UX/Forms/Rich_editor/RTF/ckeditor.javascript.txt)
- __Spinners__
  - __Buttons__
    - [ladda (JavaScript)](UX/Forms/Spinners/Buttons/ladda.javascript.txt)
  - __General__
    - [spinkit (CSS)](UX/Forms/Spinners/General/spinkit.css.txt)

### General ###

- __Theory__
  - [UX animations (Theory)](UX/General/Theory/UX_animations.theory.txt)
  - [UX consent (Theory)](UX/General/Theory/UX_consent.theory.txt)
  - [UX interactions (Theory)](UX/General/Theory/UX_interactions.theory.txt)
  - [UX mobile (Theory)](UX/General/Theory/UX_mobile.theory.txt)
  - [UX general (Theory)](UX/General/Theory/UX_general.theory.txt)
  - [UX forms (Theory)](UX/General/Theory/UX_forms.theory.txt)
  - [UX performance (Theory)](UX/General/Theory/UX_performance.theory.txt)
  - [usability (Theory)](UX/General/Theory/usability.theory.txt)

### Information structure ###

- __Layout__
  - __Bricks__
    - [masonry (JavaScript)](UX/Information_structure/Layout/Bricks/masonry.javascript.txt)
  - __Sticky header__
    - [headroom.js (jQuery)](UX/Information_structure/Layout/Sticky_header/headroom.js.jquery.txt)
- __Presentations__
  - __Web__
    - [fullpage.js (jQuery)](UX/Information_structure/Presentations/Web/fullpage.js.jquery.txt)
- __Tables__
  - [ngtable (Angular)](UX/Information_structure/Tables/_ngtable.angular.txt)
  - [ng-grid (Angular)](UX/Information_structure/Tables/ng-grid.angular.txt)

### Components framework ###

- __Full__
  - __Bootstrap__
    - [bootstrap (JavaScript CSS)](UX/Components_framework/Full/Bootstrap/bootstrap.javascript_css.txt)
    - [bootlint (CLI)](UX/Components_framework/Full/Bootstrap/bootlint.cli.txt)

### Interaction ###

- __Gestures__
  - [hammer.js (JavaScript)](UX/Interaction/Gestures/hammer.js.javascript.txt)
- __Keyboard__
  - [mousetrap (JavaScript)](UX/Interaction/Keyboard/mousetrap.javascript.txt)
- __Scrolling__
  - __Animate on scroll__
    - [scrollreveal (JavaScript)](UX/Interaction/Scrolling/Animate_on_scroll/scrollreveal.javascript.txt)
    - [stroll (JavaScript)](UX/Interaction/Scrolling/Animate_on_scroll/stroll.javascript.txt)
    - [skrollr (JavaScript)](UX/Interaction/Scrolling/Animate_on_scroll/skrollr.javascript.txt)
    - [waypoints (JavaScript)](UX/Interaction/Scrolling/Animate_on_scroll/waypoints.javascript.txt)
  - __Enhanced scrolling__
    - [slimscroll (jQuery)](UX/Interaction/Scrolling/Enhanced_scrolling/_slimscroll.jquery.txt)
    - [nicescroll (jQuery)](UX/Interaction/Scrolling/Enhanced_scrolling/nicescroll.jquery.txt)
- __Orientation__
  - [parallax.js (JavaScript)](UX/Interaction/Orientation/parallax.js.javascript.txt)

### Text ###

- __Content__
  - [content strategy (Theory)](UX/Text/Content/content_strategy.theory.txt)
- __i18n__
  - __Encoding__
    - __All__
      - [histoire encodage (Theory)](UX/Text/i18n/Encoding/All/histoire_encodage.theory.txt)
      - [comparatif encodage (Theory)](UX/Text/i18n/Encoding/All/comparatif_encodage.theory.txt)
    - __Non-Unicode__
      - [summary encoding (Format)](UX/Text/i18n/Encoding/Non-Unicode/summary_encoding.format.txt)
      - [detailed encoding (Format)](UX/Text/i18n/Encoding/Non-Unicode/detailed_encoding.format.txt)
    - __Unicode__
      - [unicode (Format)](UX/Text/i18n/Encoding/Unicode/unicode.format.txt)
      - [utf8 (Format)](UX/Text/i18n/Encoding/Unicode/utf8.format.txt)
      - [utf16 ucs2 (Format)](UX/Text/i18n/Encoding/Unicode/utf16_ucs2.format.txt)
      - [utf32 ucs4 (Format)](UX/Text/i18n/Encoding/Unicode/utf32_ucs4.format.txt)
  - __General__
    - [gtk internationalization (GTK)](UX/Text/i18n/General/gtk_internationalization.gtk.txt)
    - [c++ internationalization (C++)](UX/Text/i18n/General/c++_internationalization.c++.txt)
  - __Translation__
    - __Library__
      - __Extraction__
        - [gettext (Many)](UX/Text/i18n/Translation/Library/Extraction/gettext.many.txt)
        - [i18n (Node)](UX/Text/i18n/Translation/Library/Extraction/i18n.node.txt)
      - __Formats__
        - [po2json (Node CLI)](UX/Text/i18n/Translation/Library/Formats/po2json.node_cli.txt)
      - __Replacement__
        - [angular translate (Angular)](UX/Text/i18n/Translation/Library/Replacement/angular_translate.angular.txt)
        - [jed (JavaScript)](UX/Text/i18n/Translation/Library/Replacement/jed.javascript.txt)
  - [internationalization (Theory)](UX/Text/i18n/internationalization.theory.txt)

## RPC ##

### Inter process ###

- __HTTP__
  - __Body__
    - [body-parser multiparty multer (Express)](RPC/Inter_process/HTTP/Body/body-parser_multiparty_multer.express.txt)
  - __Content negotiation__
    - [mime (Node)](RPC/Inter_process/HTTP/Content_negotiation/mime.node.txt)
    - [negotiator accepts (Node)](RPC/Inter_process/HTTP/Content_negotiation/negotiator_accepts.node.txt)
    - [vary (Node)](RPC/Inter_process/HTTP/Content_negotiation/vary.node.txt)
  - __General__
    - [send (Node)](RPC/Inter_process/HTTP/General/send.node.txt)
  - [HTTP (Protocol)](RPC/Inter_process/HTTP/HTTP.protocol.txt)
  - __Headers__
    - [content-disposition (Node)](RPC/Inter_process/HTTP/Headers/content-disposition.node.txt)
  - __Methods__
    - [method-override (Express)](RPC/Inter_process/HTTP/Methods/method-override.express.txt)
  - __Statuses__
    - [statuses (Node)](RPC/Inter_process/HTTP/Statuses/statuses.node.txt)
  - __Streaming__
    - [range-parser (Node)](RPC/Inter_process/HTTP/Streaming/range-parser.node.txt)
- __URI routing__
  - __Client side__
    - [redux-simple-router (Redux)](RPC/Inter_process/URI_routing/Client_side/redux-simple-router.redux.txt)
    - [react-router (React)](RPC/Inter_process/URI_routing/Client_side/react-router.react.txt)
  - __Server side__
    - [vhost (Express)](RPC/Inter_process/URI_routing/Server_side/vhost.express.txt)

### Messages tasks ###

- __Task coordination__
  - [orchestrator (Node)](RPC/Messages_tasks/Task_coordination/orchestrator.node.txt)
  - [swf (AWS)](RPC/Messages_tasks/Task_coordination/swf.aws.txt)
- __Task queue__
  - [sqs (AWS)](RPC/Messages_tasks/Task_queue/sqs.aws.txt)

### Realtime ###

- __Realtime server__
  - [express.io (Express)](RPC/Realtime/Realtime_server/express.io.express.txt)
- __WebSocket__
  - __Server__
    - [WebSocket (Protocol)](RPC/Realtime/WebSocket/Server/WebSocket.protocol.txt)
    - [engine.io (Node)](RPC/Realtime/WebSocket/Server/engine.io.node.txt)
    - [ws (Node CLI)](RPC/Realtime/WebSocket/Server/ws.node_cli.txt)
    - [socket.io (Node)](RPC/Realtime/WebSocket/Server/socket.io.node.txt)

### Web client ###

- __Simple web client__
  - __File downloads__
    - [download (Node CLI)](RPC/Web_client/Simple_web_client/File_downloads/download.node_cli.txt)
  - __Multi protocols__
    - [curl (CLI)](RPC/Web_client/Simple_web_client/Multi_protocols/curl.cli.txt)
  - __HTTP__
    - __Isomorphic__
      - [superagent (JavaScript)](RPC/Web_client/Simple_web_client/HTTP/Isomorphic/superagent.javascript.txt)
    - __General__
      - [request (Node)](RPC/Web_client/Simple_web_client/HTTP/General/request.node.txt)
- __Web scraping crawling__
  - __Crawler__
    - [simplecrawler (Node)](RPC/Web_client/Web_scraping_crawling/Crawler/simplecrawler.node.txt)

### Web server ###

- __HTTP server__
  - __Directory listing__
    - [serve-index (Express)](RPC/Web_server/HTTP_server/Directory_listing/serve-index.express.txt)
  - __General__
    - [glacier (AWS)](RPC/Web_server/HTTP_server/General/glacier.aws.txt)
    - [st (Express)](RPC/Web_server/HTTP_server/General/_st.express.txt)
    - [s3 (AWS)](RPC/Web_server/HTTP_server/General/s3.aws.txt)
    - [serve-static (Express)](RPC/Web_server/HTTP_server/General/serve-static.express.txt)
  - __For development__
    - [http-server (CLI)](RPC/Web_server/HTTP_server/For_development/http-server.cli.txt)
- __REST API generation__
  - __Declarative opiniated__
    - [swagger (HTTP)](RPC/Web_server/REST_API_generation/Declarative_opiniated/swagger.http.txt)
- __Web framework__
  - __Declarative__
    - [sails (Express)](RPC/Web_server/Web_framework/Declarative/sails.express.txt)
  - __Minimalist__
    - [express (Node)](RPC/Web_server/Web_framework/Minimalist/express.node.txt)

## Utilities ##

### Date time ###

- __Date time general__
  - __Date picker__
    - [bootstrap-datepicker (Bootstrap)](Utilities/Date_time/Date_time_general/Date_picker/bootstrap-datepicker.bootstrap.txt)
  - __Date popovers__
    - [jquery-timeago (jQuery)](Utilities/Date_time/Date_time_general/Date_popovers/jquery-timeago.jquery.txt)
  - __Utilities__
    - [moment (JavaScript)](Utilities/Date_time/Date_time_general/Utilities/moment.javascript.txt)

### Strings ###

- __Strings general__
  - __Manipulation__
    - __Concatenation__
      - [gulp-concat (Gulp)](Utilities/Strings/Strings_general/Manipulation/Concatenation/gulp-concat.gulp.txt)
      - [gulp-header-footer (Gulp)](Utilities/Strings/Strings_general/Manipulation/Concatenation/gulp-header-footer.gulp.txt)
    - __Utilities__
      - [underscore.string (JavaScript)](Utilities/Strings/Strings_general/Manipulation/Utilities/underscore.string.javascript.txt)
  - __Diff__
    - [comm (CLI)](Utilities/Strings/Strings_general/Diff/comm.cli.txt)
    - __VCDiff__
      - [xdelta (CLI)](Utilities/Strings/Strings_general/Diff/VCDiff/xdelta.cli.txt)
      - [vcdiff (Format)](Utilities/Strings/Strings_general/Diff/VCDiff/vcdiff.format.txt)
    - __Patch__
      - [patch (CLI)](Utilities/Strings/Strings_general/Diff/Patch/patch.cli.txt)
    - [cmp (CLI)](Utilities/Strings/Strings_general/Diff/cmp.cli.txt)
    - [diff3 (CLI)](Utilities/Strings/Strings_general/Diff/diff3.cli.txt)
    - [diff sdiff (CLI)](Utilities/Strings/Strings_general/Diff/diff_sdiff.cli.txt)
  - __Encoding__
    - [base64 base32 hex octal (Format)](Utilities/Strings/Strings_general/Encoding/base64_base32_hex_octal.format.txt)
  - __Matching__
    - __Globbing__
      - [minimatch (Node)](Utilities/Strings/Strings_general/Matching/Globbing/minimatch.node.txt)
    - __RegExp__
      - [gulp-replace (Gulp)](Utilities/Strings/Strings_general/Matching/RegExp/gulp-replace.gulp.txt)

