# Project of the Week: Rust
Learning Rust Fundamentals

## Week 1

Compiling and Running Rust (done in separate steps)
* Compile first:
    * _rustc filename.rs_
    * Shows executable file <filename> and source file filename.rs
* Then run:
    * ./filename
* Different from dynamic languages like Python or Javascript where programs are compiled and run together 

Package Management in Rust
*  Cargo
    * Tool used to manage Rust projects
    * Handles building code, downloading libraries code depends on, building said libraries
    * _cargo new project_name_
        * Creates new dir and project and files inside dir
    * Anatomy of cargo project
        * Cargo.toml
        * Src 
        * Initializes new git repo along with .gitignore
    * Cargo.toml? What is that?

      anatomy:

          [package]
      
            Name = “….”
      
            Version = “0.1.0”
      
            Edition = “2023"
   
           [dependencies]
      
        * package
            * Lines underneath configure package
        * dependecies
            * List any project dependencies 
    * Building and running cargo project
        * _Cargo build_
            * Creates executable file in target/debug/project_name
            * Cargo puts binary in debug dir by default 
        * _Cargo run_
            * Builds and runs executable in one step 
        * _Cargo check_
            * Check if code compiles without producing an executable
    * Building software for release
        * _Cargo build —release_
            * Creates executable in target/release instead of target/debug
            * Meant for when program is ready to be widely used/adopted to users

Formatting Code
   * _Rustfmt filename.rs_
      * Formats code with proper indentation/spacing/etc...
    
## Week 2

Variables and Mutability
 * 
