video_downloader_sources = files([
  '__init__.py',
  '__main__.py',
  'youtube_dl_formats.py',
  'youtube_dl_monkey_patch.py',
  'youtube_dl_slave.py',
])
python_sources_for_linting += video_downloader_sources

install_data(video_downloader_sources, install_dir: moduledir / 'downloader')
