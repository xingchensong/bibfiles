# bibfiles
My bibtex for paper reference. 

Following tsinghua standards (see **section3.3** in [清华大学研究生学位论文写作指南-202007](https://github.com/tuna/thuthesis/files/4929046/202007.pdf)), the format of bibtex can be seen as:
```bib
[author] [title] (editor) [booktitle] [address] [publisher] [year] [pages] (urldate) (url)
% NOTE: for IEEE standards, info in [] is required, info in () is optional
% NOTE: for tsinghua standards, both of them are required
```


## Template:
```bib
%% conference
@inproceedings{conferencename/id,
  author    = {},
  title     = {},
  editor    = {},
  booktitle = { ()},
  address   = {},
  pages     = {},
  publisher = {{}},
  year      = {},
  url       = {},
  doi       = {},
  urldate   = {},
}
%% journal
@article{journalname/id,
  author    = {},
  title     = {},
  editor    = {},
  journal   = {},
  volume    = {},
  number    = {},
  pages     = {},
  year      = {},
  url       = {},
  doi       = {},
  urldate   = {},
}
%% arXiv
@article{arxiv/id,
  author    = {},
  title     = {},
  editor    = {},
  journal   = {arXiv preprint},
  year      = {},
  url       = {},
  doi       = {},
  urldate   = {},
}
```
