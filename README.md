# my.porfolio
# Create a new repository
mkdir my-portfolio
cd my-portfolio
git init

# Create initial portfolio file
cat > portfolio.md << 'EOF'
# My Portfolio

## About Me
Name: [Mozamel]
Major: Computer Programming

## Skills
- Programming: Basic
- Git: Learning

## Projects
- Project 1: TBD
- Project 2: TBD

## Contact
Email: mmohammad40@myseneca.ca
EOF

git add portfolio.md
git commit -m "Initial portfolio"
# Create and switch to desktop branch
git checkout -b desktop-updates

# Edit portfolio.md - update Skills section
# Change the Skills section to:
