# hello-world
  $rs=$dbh->query("select cat_id,yh_id,qidian,zhdian,tujdi,chfshj,chfshj1,sxzuowei,sxjlche,xingzhi,feiyong,jiage,wc_time,kaishij,jieshj,times,type,status,zushun,plstatus from hc_chek_order  where yh_id='$id' and status=7 and zushun=3 order by wc_time desc");
