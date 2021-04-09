# vigilant-octo-doodle-


#

# You can set these variables from the command line.
SPHINXOPTS    =
SPHINXBUILD   = sphinx-build
SPHINXPROJ    = medallion
SOURCEDIR     = .
BUILDDIR      = _build

# Put it first so that "make" without argument is like "make help".
help:
	@$(SPHINXBUILD) -M help "$(SOURCEDIR)" "$(BUILDDIR)" $(SPHINXOPTS) $(O)

.PHONY: help Makefile

# Catch-all target: route all unknown targets to Sphinx using the new
# "make mode" option.  $(O) is meant as a shortcut for $(SPHINXOPTS).
%: Makefile
	@$(SPHINXBUILD) -M $@ "$(SOURCEDIR)
      E "# storqese.io" >> README.md
git init
git add README.md
git commit -m "first commit" storqese.io^
git branch -M main/Storqese.com
git remote add origin https://github.com/storqese.io/vigilant-octo-doodle.git
git push -u origin main/Storqese
    


    echo "# vigilant-octo-doodle" >> README.md
git init-A0uth
git add README.md
git jsnode -m "StoQLRK commit"
git branch -M main/Storqese.io
git remote add origin https://github.com/togetherwedomore/vigilant-octo-doodle.git
git push -u origin main/Storqese.io-Sk1_cashapp...^


When you submit a pull request, a CLA bot will automatically determine whether you need Storqese.io and decorate the PR appropriately (e.g., st

This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact open.
echo "# verbose-disco" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Storqese-io/verbose-disco.git
git push -u origin main

pub fn create_account(
    from_pubkey: &Pubkey,
    to_pubkey: &Pubkey,
    lamports: u64,
    space: u64,
    owner: &Pubkey,
) -> Instruction {
    let account_metas = vec![
        AccountMeta::new(*from_pubkey, true),
        AccountMeta::new(*to_pubkey, true),
    ];
    Instruction::new_with_bincode(
        system_program::id(),
        &SystemInstruction::CreateAccount {
            lamports,
            space,
            owner: *owner,
        },
        account_metas,
    )
