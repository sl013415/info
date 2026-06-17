# info

BlobEndpoint=https://temptestcap.blob.core.windows.net/;QueueEndpoint=https://temptestcap.queue.core.windows.net/;FileEndpoint=https://temptestcap.file.core.windows.net/;TableEndpoint=https://temptestcap.table.core.windows.net/;SharedAccessSignature=sv=2026-02-06&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-06-19T10:45:50Z&st=2026-06-17T02:30:50Z&spr=https&sig=ACWZ9ioR9NmfFKY2VPKXiTDk2IQMFkS0VwPJmBCByNY%3D

az storage blob upload-batch \
  --destination asfndaslfjnxah \
  --source ./dist \
  --sas-token "sv=2026-02-06&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-06-19T10:45:50Z&st=2026-06-17T02:30:50Z&spr=https&sig=ACWZ9ioR9NmfFKY2VPKXiTDk2IQMFkS0VwPJmBCByNY%3D" \
  --account-name temptestcap


sv=2026-02-06&ss=bfqt&srt=sco&sp=rwdlacupiytfx&se=2026-06-19T10:45:50Z&st=2026-06-17T02:30:50Z&spr=https&sig=ACWZ9ioR9NmfFKY2VPKXiTDk2IQMFkS0VwPJmBCByNY%3D