## commentsにindexを付与
`alter table comments add index comments_post_id_created_at_idx(post_id,created_at desc);`