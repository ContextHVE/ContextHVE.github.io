---
layout: default
title: ContextHVE
---

<div class="post">
	<h2 class="pageTitle">Video Reconstruction Demos</h2>
    <p align="center">
	<img src="{{ '/assets/img/pipeline.jpg' | relative_url }}" alt="">
    </p>
	<p></p>
	<table border="0"> <!-- 表格边框设置为1 -->
	<tr></tr>
    <tr>Editing the video with original condition.This result primarily reflects the ability to complete the mask region and to maintain the original characteristics of the scene/person in the original video. Here, the characters in the original video are directly used to complete the video. Note that, unlike the method of incorporating original image priors into noise when initializing the noise, our initial noise is entirely randomly generated. This means that the condition image priors are completely derived from ContextNet, and this is also the reason for the addition of the Reconstruction experiment.</tr>

    <tr> <!-- 表格的一行 -->
        <th style="width: 456px;">Ground Truth</th> <!-- 表头单元格 -->
        <th style="width: 456px;">Pose</th> <!-- 表头单元格 -->
    </tr>
    <tr> <!-- 表格的一行 -->
        <th style="width: 456px;">Masked Scene</th> <!-- 表头单元格 -->
        <th style="width: 456px;">Ours</th> <!-- 表头单元格 -->
    </tr>
    </table>
	<table border="0"> <!-- 表格边框设置为1 -->
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
            <video width="912" height="512" controls>
                <source src="/assets/img/recon/060000-clip_0000011001_gt_clip_0000011001_gt_good.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
            <video width="912" height="512" controls>
                <source src="/assets/img/recon/060000-clip_0000011134_gt_clip_0000011134_gt_good.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
            <video width="912" height="512" controls>
                <source src="/assets/img/recon/060000-clip_0000011164_gt_clip_0000011164_gt_good.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
            <video width="912" height="512" controls>
                <source src="/assets/img/recon/060000-clip_0000011165_gt_clip_0000011165_gt_half.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
            <video width="912" height="512" controls>
                <source src="/assets/img/recon/060000-clip_0000011179_gt_clip_0000011179_gt_good.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
            <video width="912" height="512" controls>
                <source src="/assets/img/recon/060000-clip_0000011186_gt_clip_0000011186_gt_good.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
    <tr> <!-- 表格的另一行 -->
        <td> <!-- 表格的单元格 -->
            <video width="912" height="512" controls>
                <source src="/assets/img/recon/060000-clip_0000011192_gt_clip_0000011192_gt_half.mp4" type="video/mp4">
                您的浏览器不支持视频标签。
            </video>
        </td>
    </tr>
</table>

</div>
