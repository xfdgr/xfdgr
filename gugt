package com.example.demo.entity;

import com.baomidou.mybatisplus.annotation.IdType;
import com.baomidou.mybatisplus.annotation.TableField;
import com.baomidou.mybatisplus.annotation.TableId;
import lombok.Data;

import java.time.LocalDateTime;
import java.util.ArrayList;
import java.util.List;

@Data
public class User {
    @TableId(type = IdType.AUTO)
    private Long id;

    private String account;

    private String pwd;

    private String userDesc;

    private String userHead;

    private LocalDateTime createTime;

    private Long role;

    private String nickname;

    private String email;

    private String tags;
}
